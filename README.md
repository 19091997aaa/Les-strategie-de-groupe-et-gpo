# TP : Mise en place de GPO (Active Directory)

Dans ce TP, j'ai configuré une stratégie de groupe pour interdire l'accès au Panneau de Configuration sur les postes clients.

## Preuve de fonctionnement
Voici le résultat sur le poste client Windows 11 après un `gpupdate /force` :

![Résultat GPO](der%20de%20der.png)

*Légende : Le message de restriction confirme que l'utilisateur ne peut plus accéder aux paramètres.*
