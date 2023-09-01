# Avaliação-M7-Inteli - Eduardo França Porto

### **Backend**

O dockerfile do backend é baseado no mesmo que desenvolvi na ponderada e ele expõem a porta 8000.
https://hub.docker.com/r/eduardoporto/backend-prova


### **Frontend**

O dockerfile do frontend também é baseado no da ponderada que executei antes e o mesmo deixa aberta a porta 3000.
https://hub.docker.com/r/eduardoporto/front-prova

### **Docker - compose**

O arquivo docker compose pega do dockerhub as imagens que foram construidas a partir dos dockerfiles citados acima e novamente expõem as porta 8000 e 3000 do back e front respectivamente.

Para executar o projeto só é necessário acessar a pasta ráiz desse repo "Avaliacoes-M7-Inteli " e executar o comando

`docker compose up`
