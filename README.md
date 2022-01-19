# docker-portainer

![portainer](https://www.portainer.io/hubfs/Images/Heroes/Illustrations/SVG/Portainer_Illustrations_Crane%20-%20Hero%20copy.svg "Portainer")

Portainer Community Edition (CE) is our foundation. With over half a million regular users, CE is a powerful, open source toolset that allows you to easily build and manage containers in Docker, Docker Swarm, Kubernetes and Azure ACI.

Portainer hides the complexity of managing containers behind an easy-to-use UI. By removing the need to use the CLI, write YAML or understand manifests, Portainer makes deploying apps and troubleshooting problems so easy that anyone can do it.

<https://docs.portainer.io/>

## Prérequis

1. Assurez-vous de suivre les étapes d'installation pour votre distribution de Linux: [Instructions pour Ubuntu/Debian](https://docs.docker.com/engine/install/debian/)
2. Assurez-vous également de suivre les étapes de post-installation pour Linux: [Instructions](https://docs.docker.com/engine/install/linux-postinstall/)
3. Finalement, installez Docker-Compose: [Instructions](https://docs.docker.com/compose/install/)

## Installation

1. Copiez le fichier `.env.example` et renommez-le `.env`.
2. Indiquez l'endroit où vous voulez mettre les données dans la variable `portainer_data_folder` du fichier `.env`.
3. Exécutez la commmande suivante: `docker-compose up -d`.
4. Ouvrez l'adresse: `https://localhost:9443/`
5. Enjoy!

## Références

<https://www.portainer.io/>

<https://www.docker.com/>

<https://docs.docker.com/compose/>
