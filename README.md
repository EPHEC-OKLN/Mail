# Mail
Les mails sont un outil très important dans une entreprise car ils permettent la communication entre les employés mais aussi entre les employés et les clients de l'entreprise.<br>
Ils ont aussi un rôle d'archivage et d'authentification de la communication.<br><br>
Avoir une adresse mail professionnels permet plusieurs choses:
* Elle assure la crédibilité de votre entreprise.
* L'entreprise reste maitre des mails associé au domaine.
* Les protections contre les mails malicieux, spams, phishing, ect, sont gérer de facons centraliser<br>

## Mise en place d'un serveur Microsoft Exchange
*Durée d'exécution : Environ 60 Minutes*
### Prérequis
- [X] Processeur X64
- [X] Mémoire vive : Minimum 8 Go
- [X] Espace de stockage : Minimum 30 Go
- [X] Format de fichier NTFS
- [ ] Tous les controlers de domaines doivent exécuter Windows Server 2016 Standard ou Datacenter 
- [ ] Installer Active Directory
- [ ] Le niveau de fonctionnalité de la forêt Active Directory doit correspondre à Windows Server 2016
- [ ] Exchange prend en charge les espaces de noms DNS
Vérifiez les autorisations suivantes pour le compte utilisé pour installer Exchange 2016 :
- [ ] Membres du groupe Administrateurs de l’entreprise
- [ ] Membres du groupe Administrateurs du schéma
### Client Mail pris en charge
* Outlook 2016
* Outlook 2013
* Outlook 2010 SP2
* Outlook pour Mac pour Office 365
* Outlook pour Mac 2011
### Installation de Microsoft Exchange 2016
1. Démarrez le programme d’installation Exchange 2016 en double-cliquant sur <em>Setup.exe</em>
2. L’Assistant Installation d’Exchange Server 2016 s’ouvre. Sur la page Rechercher des mises à jour ?, choisissez l’une des options suivantes, puis cliquez sur Suivant pour continuer :
   * Se connecter à Internet et rechercher les mises à jour disponibles
   * Ne pas vérifier les mises à jour immédiatement
3. La page Copie des fichiers affiche la progression de la copie des fichiers sur le disque dur local. En règle générale, les fichiers sont copiés sur *%WinDir%\Temp\ExchangeSetup*, mais vous pouvez vérifier l’emplacement dans le journal d’installation Exchange situé dans *C:\ExchangeSetupLogs\ExchangeSetup.log*
![Copie Logo](https://i-technet.sec.s-msft.com/dynimg/IC872138.png "Copie image")
4. Sur la page Introduction, nous vous conseillons de consulter les liens relatifs à la planification de déploiement d’Exchange Server 2016 si ce n’est pas déjà fait. Cliquez sur Suivant pour continuer.
5. Suivant
6. Suivant
7. Paramètres recommandé
8. Selectionner le rôles des serveurs
9. Choisir l'emplacement d'installation
10. Spécifier le nom de votre organisation
### Sources
https://technet.microsoft.com/fr-fr/library/bb124778(v=exchg.160).aspx



