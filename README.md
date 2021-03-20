# Microservice kurs med Casper & Jesper


## Avhengigheter
- [Dockerhub account](https://hub.docker.com/)
- [Docker desktop (mac/windows)](https://www.docker.com/get-started)
- [Docker + kubernetes for linux](https://kubernetes.io/docs/tasks/tools/install-minikube/)
- [Skaffold](https://skaffold.dev/docs/install/)

## Kjøre prosjektet
prosjektet kan kjøres ved å kjøre kommandoen ```skaffold dev```
## Tjenester
- client: brukergrensesnittet til applikasjonen
- posts: styrer logikken rundt posts
- comments: styrer logikken rundt kommentarer på posts
- query: gjør forenklede spørringer for client
- event-bus: prosesserer nettverkskall i tjenesten

