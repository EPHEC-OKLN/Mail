# Tâches réalisées
Lors de la mise en place du serveur mail. Nous avons dû mettre Exchange pour permettre la gestion de la boîte mail.

Pour ce fait, nous avons télécharger Exchange 2016 u3. Par la suite, nous avons remarqué que la version 3 n'était pas complète pour être installée. Du coup, nous avons installé la version u8 et installé les différentes mises à jour du windows serveur et l'installation a pu s'effectuer correctement. 

# Problèmes rencontrés

* Problème 1 : Nous avons du attendre longtemps (3 jours) avant de pouvoir commencer à installer le service de Exchange, ce qui nous a empêcher de mettre en place le système dans les temps.
* Solution 1 : Aider les d'autres département ou offrir un accès basique (pas notre faute :/ ) à internet et à la machine virtuelle pour configurer l'ensemble des services nécessaire sur la machine.
* Problème 2 : Nous avons remarqué, trop tard, que le serveur mail disposait uniquement de 1 core et 1 processeur.
* Solution 2 : Reprendre contact avec l'équipe de gestion des machines virtuelles. 
* Problème 3 : Lorsque nous avons essayé d'installer Exchange (u3), de nombreuses erreurs d'installation, nous ont empêcher de poursuivre l'installation. Nous avons corrigé l'ensemble des erreurs excepté, l'une d'elle (Server-GUI-Mgmt-Infra). 
* Solution 3 : Nous avons corriger le problème grâce à des mises à jours systèmes et en installant la version u8 de Exchange 2016.

# Motivations des technologies/infrastructures utilisées
Nous avons choisi Exchange pour des raisons de facilité de configuration et pour une facilité de gestion des utilisateurs (lié à l'AD).

# Remarques éventuelles
Bien faire attention aux configurations du système et s'y prendre à l'avance.

# Sources

https://technet.microsoft.com/fr-fr/library/bb124778(v=exchg.160).aspx

https://technet.microsoft.com/fr-fr/library/jj991919(v=exchg.160).aspx

http://www.appitel.fr/blog/messagerie/messagerie-professionnelle-microsoft-exchange-server/

https://technet.microsoft.com/fr-fr/library/bb124778(v=exchg.160).aspx

https://technet.microsoft.com/fr-fr/library/aa996719(v=exchg.160).aspx

https://technet.microsoft.com/fr-fr/library/jj991919(v=exchg.160).aspx

https://www.microsoft.com/en-us/download/details.aspx?id=49161
