# Microsoft Entra ID & Intune Lab

Lab personnel d’infrastructure cloud Microsoft 365 réalisé sous VirtualBox.

Ce projet simule la gestion des identités, des appareils et de la sécurité d’une entreprise moderne avec Microsoft Entra ID et Microsoft Intune.

## Objectifs

- Gérer des utilisateurs et des licences dans Microsoft Entra ID.
- Enrôler et gérer un poste Windows 11 avec Microsoft Intune.
- Appliquer des stratégies de conformité et de configuration.
- Configurer Conditional Access.
- Déployer une application à distance.
- Automatiser des tâches avec PowerShell et Microsoft Graph.

## Technologies utilisées

- Microsoft Entra ID
- Microsoft Intune
- Microsoft 365
- PowerShell
- Microsoft Graph
- Windows 11
- VirtualBox
- Conditional Access

## Éléments mis en place

- Création et gestion d’utilisateurs cloud.
- Attribution des licences Microsoft Entra ID P2 et Intune Plan 1.
- Enrôlement automatique des appareils.
- Création de groupes dynamiques d’utilisateurs et d’appareils.
- Enrôlement d’un poste Windows 11 avec Microsoft Entra Join.
- Stratégie de conformité avec BitLocker, pare-feu, antivirus et mot de passe.
- Déploiement de profils de configuration avec Intune.
- Déploiement à distance de Power BI Desktop.
- Configuration d’une stratégie Conditional Access.
- Suivi de la conformité des appareils.
- Automatisation avec PowerShell et Microsoft Graph.

## Résultats

- Poste Windows 11 joint à Microsoft Entra ID.
- Appareil enrôlé dans Microsoft Intune.
- Appareil conforme aux stratégies de sécurité.
- Déploiement réussi de Power BI Desktop.
- Création automatisée d’un utilisateur via Microsoft Graph PowerShell.

## Difficultés rencontrées

- Résolution d’un problème BitLocker lié à une image ISO montée dans la machine virtuelle.
- Compréhension du conflit entre Security Defaults et Conditional Access.
- Gestion de l’appartenance automatique aux groupes dynamiques.
- Identification d’une limitation liée à l’absence d’interface Wi-Fi physique dans la machine virtuelle.

## Projet associé

[Lab Active Directory V1](https://github.com/tarekhamroun/Lab-Active-Directory-V1)

## Évolutions prévues

La prochaine version du lab portera sur une architecture hybride avec Active Directory on-premise, Microsoft Entra Connect et la synchronisation des identités.
