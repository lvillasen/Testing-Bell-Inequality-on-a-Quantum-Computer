# Testing Bell´s Inequality with Qiskit
We illustrate how to test the version of Bell´s inequality proposed by David Mermin using Qiskit.

See Brian Greene's youtube video for a clear explanation of this version of Bell's inequality.


```
                                  EPR vs Quantum MECHANICS

The 2022 Nobel Prize in Physics was awarded to Alain Aspect, John Clauser and Anton Zeilinger
"for experiments with entangled photons, establishing the violation of Bell inequalities and pioneering quantum information science"

We measure the spin of two entangled particles A and B which have total spin equal to zero along 3 axes rotated 0 (Axis 1), 120 (Axis 2) y 240 degrees (Axis 3) on the XZ plane



A 0 corresponds to spin up and 1 to spin down along the particular axis used for that measurement  


Measurement A <---------------------------- 2 spin 1/2 particles with total S = 0 -------------------> Measurement B



A1B1 means we measure along axis1 for particle A and axis 1 for particle B, A1B2 means we measure along axis1 for particle A and axis 2 for particle B and so on.

Assuming the spins are determined (by hidden variables) prior to the measurements, the EPR prediction would be


A             B	          Anti-Correlations		 Fraction of Anti-Correlated Measurements

123	      123	 [A1B1,A1B2,A1B3,A2B1,A2B2,A2B3,A3B1,A3B2,A3B3]			 

000 	      111 	 [1, 1, 1, 1, 1, 1, 1, 1, 1] 			 9 / 9
001 	      110 	 [1, 1, 0, 1, 1, 0, 0, 0, 1] 			 5 / 9
010 	      101 	 [1, 0, 1, 0, 1, 0, 1, 0, 1] 			 5 / 9
011 	      100 	 [1, 0, 0, 0, 1, 1, 0, 1, 1] 			 5 / 9
100 	      011 	 [1, 0, 0, 0, 1, 1, 0, 1, 1] 			 5 / 9
101 	      010 	 [1, 0, 1, 0, 1, 0, 1, 0, 1] 			 5 / 9
110 	      001 	 [1, 1, 0, 1, 1, 0, 0, 0, 1] 			 5 / 9
111 	      000 	 [1, 1, 1, 1, 1, 1, 1, 1, 1] 			 9 / 9


```
According to EPR the fraction of anti-correlated measurements is > 5/9 (Bell's inequality: Anti-Corr(A,B) > 56%) but the experiments produce 50% anti-correlated measurements.

Quantum Mechanics violates Bell's inequality and therefore the Einstein-Podolsky-Rosen argument is not valid and Quantum Mechanics is a non-local theory.


**References**

Mermin, N.D.: Bringing home the atomic world: Quantum mysteries for anybody. American Journal of Physics 49, 940-943 (1981).

Answering Mermin’s Challenge with the Relativity Principle by Mark Stuckey https://www.physicsforums.com/insights/answering-mermins-challenge-with-wilczeks-challenge

Youtube video by Brian Greene: https://www.youtube.com/watch?v=UZiwtfrisTQ

