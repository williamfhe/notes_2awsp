# Amazon VPC

Amazon Virtual Private Cloud (VPC) est un service qui va nous permettre de gérer des réseaux virtuels et d'isoler nos resources entre elles.

Lorsque l'on crée le VPC, on va devoir lui associer une plage d'IP [CIDR](https://en.wikipedia.org/wiki/Classless_Inter-Domain_Routing).

Il va être ensuite possible de découper notre VPC en plusieurs sous-réseaux appelés subnets.

Grâce à nos subnets on va pouvoir isoler nos applications entre elles, par exemple séparer nos serveurs web des bases de données.

## Notions importantes

Une région peut contenir plusieurs VPC.

Un VPC ne peut couvrir qu'une seule région.

Un VPC peut contenir plusieurs subnets.

Un Subnet ne peut être contenu que dans un VPC.

Un Subnet ne peut couvrir qu'une seule Zone de Disponibilité.

Une Zone de Disponibilité peut contenir plusieurs Subnets.

## Liens intéresants

https://aws.amazon.com/fr/vpc/

## Vidéos

https://www.youtube.com/watch?v=hiKPPy584Mg

https://www.youtube.com/watch?v=gUesnoDzNr4