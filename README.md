# Lab8
budowanie obrazu
docker buildx b -f Dockerfile_classic -t milenarunets/lab:cla --sbom=true --provenance=true --push .
Analiza obrazu 
![image](https://github.com/Indrawi1/Lab8/assets/98088474/2b4e2a32-0b7d-4796-9a27-d1dfee99efb3)
Jak widać mam 1 zagrożenie critical i 1 high, ale 
![image](https://github.com/Indrawi1/Lab8/assets/98088474/0dea7db6-564a-4c6e-95c6-0bc8c15cb5b5)
jak widać ze zdjęcia fix zagrożenia jest w wersji json-schema@^0.4.0, którą zainstalowałam, ale w analize scout jest napisane że używam json-schema@^0.2.3
![image](https://github.com/Indrawi1/Lab8/assets/98088474/bd1dbbdb-e6e7-429f-8456-afbc56c99e6c)
i podobna sytuacja z qs@^6.5.3



