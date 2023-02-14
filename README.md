# Bell-Inequality-in-Qiskit
We illustrate how to test the version of the Bell inequality proposed by David Mermin using Qiskit

```
EXPERIMENTO EPR vs MECANICA CUANTICA

Premio Nobel de Física 2022 al francés Alain Aspect, al estadounidense John Clauser y al austriaco Anton Zeilinger

Medimos el espín de las partículas A y B en 3 ejes que estám de 0 (Eje 1), 120 (Eje 2) y 240 grados (Eje 3)



El espín medido 0 corresponde a spin up y el 1 a spin down a lo largo del eje respectivo 


Medición A ---------------------------------Par A B entrelazados con S = 0 -----------------------Medición B



Medimos el espín A y B en ángulos de 0, 120 0 240 grados


Plan A	 Plan B	 Correlaciones			 		Fracción Anticorrelacionados

123	 123	 [A1B1,A1B2,A1B3,A2B1,A2B2,A2B3,A3B1,A3B2,A3B3]			 

000 	 111 	 [0, 0, 0, 0, 0, 0, 0, 0, 0] 			 9 / 9
001 	 110 	 [0, 0, 1, 0, 0, 1, 1, 1, 0] 			 5 / 9
010 	 101 	 [0, 1, 0, 1, 0, 1, 0, 1, 0] 			 5 / 9
011 	 100 	 [0, 1, 1, 1, 0, 0, 1, 0, 0] 			 5 / 9
100 	 011 	 [0, 1, 1, 1, 0, 0, 1, 0, 0] 			 5 / 9
101 	 010 	 [0, 1, 0, 1, 0, 1, 0, 1, 0] 			 5 / 9
110 	 001 	 [0, 0, 1, 0, 0, 1, 1, 1, 0] 			 5 / 9
111 	 000 	 [0, 0, 0, 0, 0, 0, 0, 0, 0] 			 9 / 9

```
De acuerdo con EPR la fracción de anticorrelaciones debe ser > 5/9 (la desigualdad de Bell es AntiCorr(A,B) > 56%) pero el experimento arroja 50%

Es decir que la MC viola la desigualdad de Bell y por lo tanto la visión de EPR no coincide con el experimento (la MC es no local)

