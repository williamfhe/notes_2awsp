# AWS Auto Scaling

AWS Auto Scaling va automatiquement ajuster la capacité de nos resources pour répondre à nos besoins.

L'auto Scaling peut gérer plusieurs ressources comme :
- Les Instances EC2
- Les tables et indices DynamoDB
- Les répliques Aurora

Utiliser l'auto scaling peut par exemple nous permettre de déployer de nouvelles instances de nos applications, via la création de nouvelles instances EC2 afin de répondre à un pic de traffic.

Toujours dans l'exemple de EC2, l'auto scaling est déclenchable via des alarmes configurées dans CloudWatch et déploie de nouvelles instances en suivant une configuration de lancement configurée dans EC2.

## Liens intéresants

https://aws.amazon.com/fr/autoscaling/

https://aws.amazon.com/fr/ec2/autoscaling/

## Vidéos

https://www.youtube.com/watch?v=NuYTRLt4dMA

https://www.youtube.com/watch?v=jvMoWjsP7Pk