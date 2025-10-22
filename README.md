# qa-final-project-java

Poiectul acesta reprezinta structura completa a unui proiect de autmatizare, care include: repository de Git, creare de imagine cu container Docker si crearea unui pipeline CI/CD de testare in GitHubActions.

Pentru rularea locala, se executa comanda mvn test ori in terminalul de windows ori prin introducerea acesteia in interiorul fisierului Dockerfile. In cazul proiectului meu am folosit introducerea comenzii ca parte a fisierului de containerizare, "Docker" .

Construirea imaginii Docker am facut-o prin pornirea Docker-Engine si apoi rularea comenzilor:
docker build -t qa-final-project-java .
docker run --rm qa-final-project-java

