
## Création d'un VPC avec avec des sous-reseaux public et privé

Dans cet exemple, nous allons créer un VPC avec des sous-reseaux public et privé

![image](https://github.com/momodou44/vpc_public_private_subnet/assets/66375343/ef4ae430-1461-4994-a965-43b031348dd4)


### Description

Cet exemple montre comment créer un VPC que vous pouvez utiliser pour des serveurs dans un environnement de production.

Pour améliorer la résilience, vous pouvez déployer les serveurs dans deux zones de disponibilité, en utilisant un groupe de mise à l'échelle automatique et un équilibreur de charge d'application. Pour plus de sécurité, vous pouvez déployer les serveurs dans des sous-réseaux privés. Les serveurs reçoivent les requêtes par l'intermédiaire de l'équilibreur de charge. Les serveurs peuvent se connecter à l'internet en utilisant une passerelle NAt. Pour améliorer la résilience, vous pouvez déployer la passerelle NAt dans les deux zones de disponibilité.



