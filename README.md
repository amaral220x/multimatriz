# multimatriz
Multiplicador de Matrizes em C feito para matéria de Programação Concorrente!

Anotando resultados:
Matriz 500x500 = Multiplicação = (0,449292+0,435822+ 0,434616) / 3 = 0,43991 Total = (2,160949 + 1,298406+ 1,244312)/3 = 1,567889
Matriz 1000x1000 = (3,701855 + 4,071212 + 3,840664) / 3 ~= 3,87124  Total = (6,826504 + 7,185286 + 6,981318)/3 ~= 6,997702
Matriz 2000x2000 = (44,959162 + 43,935868 + 43,694503) / 3 = 44,196511 Total = (57,825528 + 56,665063 + 56,643811)/3 ~= 57,0448006

Prevendo ganhos (TempoSequencial/TempoConcorrente) em um cenário com 4 threads: 

500x500 =   1,567889 / 1,127979 + 0,1099775  = 1,567889 / 1,2379565 = 1,266
1000x1000 = 6,997702 / 3,126462 + 0,96781 = 6,997702 / 4,094272 = 1,70
2000x2000 = 57,0448006 / 12,8482896 + 11,04912775 = 57,0448006 / 23,89741735 = 2,387