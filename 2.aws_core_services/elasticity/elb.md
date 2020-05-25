# Amazon ELB

Amazon Elastic Load Balancer (ELB) est un service qui va nous fournir des load balancer avec de répartir efficacement le traffic dans notre infrastructure.

ELB peut répartir le traffic à travers plusieurs Zones de Disponibilité.

Il existe trois types de load balancer dans ELB:
- ALB: Application Load Balancer, adapté pour le traffic HTTP et HTTPS. Travaille sur la couche 7 du modèle OSI.

- NLB: Network Load Balancer, adapté pour le traffic TCP, UDP et TLS. Travaille sur la couche 4 du modèle OSI.

- CLB: Classic Load Balancer, conçu pour les applications EC2 Classic.


Le Load Balancer utilise ce que l'on appelle des Targets Groupes (ou groupes cibles en Français) afin de savoir où envoyer le traffic.

## Liens intéresants

https://aws.amazon.com/fr/elasticloadbalancing/

## Vidéos

https://www.youtube.com/watch?v=66vwXpmK9NI

https://www.youtube.com/watch?v=qpHLRc4Qt1E