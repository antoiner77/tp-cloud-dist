# tp-cloud-dist

Le but de ce TP est d'automatiser la creation d'un site d'hebergement de screenshot !
Pour ce TP vous devez disposer d'un compte AWS (gratuit)
Vous allez avec ce TP creer: Un serveur EC2, un Bucket S3, un groupe d'auto-scalling, et un loadbalancer !



# Avant de commencer le TP:

 Step0: Configuration des Droits (role & strategie Configuration des droits entre notre serveur et AWS)

IAM -> Strategie

1) Nouvelle strategie

Nous voulons autoriser un serveur EC2 à contacter le service s3
Nous voulons qu'il puisse ecrire, pas besoins de plus de permission
Nous voulons aussi qu'il n'ai access qu'a notre bucket et pas a d'autre de notre compte (Utilisation des "arn" pour identifier le bucket)

IAM -> Role

2) Creation du role

Le role doit etre utilisable sur un serveur EC2, c'est une sorte de groupe que l'on assigne a notre serveur pour lui autoriser des actions. Il faut donc ajouter la strategie crée dans l'etape 1 a notre role.




# Pour l'etape 3:
M'envoyer un mail sur: antoine.roy77@gmail.com avec votre ID de compte AWS (necessaire pour continuer le TP)

Pensez a bien supprimer toutes les ressources une fois le TP fini, et a supprimer le compte si besoins.

