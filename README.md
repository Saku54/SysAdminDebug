# SysAdminDebug
Debug GUI for Virtual Machine


🇫🇷 Version française
Description
Ce script PowerShell fournit une interface graphique simple pour diagnostiquer rapidement l’état de santé d’une machine virtuelle Windows. Il permet d’exécuter plusieurs tests système essentiels, de manière sélective.

Fonctionnalités disponibles :

✅ Vérification de l’espace disque

✅ Surveillance de l'utilisation CPU / RAM

✅ Test de connectivité réseau (ping)

✅ Test de port et pare-feu (netstat) spécification du port

✅ Vérification des mises à jour Windows en attente

✅ Vérification de la configuration WSUS

✅ Analyse des derniers logs systèmes

✅ Recherche d’un utilisateur dans l’Active Directory

Prérequis
PowerShell 5.1 ou supérieur

Droits administrateur

Accès aux modules ActiveDirectory pour la recherche AD

Utilisation
Exécutez le script avec PowerShell en tant qu’administrateur :

.\Outil-Diagnostic-VM.ps1

Dans l’interface :

Cochez les tests à exécuter.

Renseignez les champs requis (IP, port, utilisateur AD).

Cliquez sur "Lancer l'audit" pour commencer.

Consultez les résultats dans la zone prévue.

Résultat :

Une barre de progression indique l’état de l’audit.

Chaque test sélectionné affiche un retour détaillé.

Les erreurs sont gérées et affichées dans les résultats.

🇬🇧 English Version
🛠️ Usage Documentation – PowerShell Script Outil-Diagnostic-VM.ps1
Description
This PowerShell script provides a GUI for quickly checking the health status of a Windows virtual machine. It allows you to selectively run several essential system checks.

Available Features : 
✅ Disk space check

✅ CPU / RAM usage monitoring

✅ Network connectivity test (ping)

✅ Port and firewall test (netstat) port can be specified

✅ Pending Windows Updates check

✅ WSUS configuration check

✅ Latest system error logs analysis

✅ Active Directory user search

Requirements
PowerShell 5.1 or later

Administrator privileges

ActiveDirectory module installed (for AD search)

Usage
Run the script in PowerShell as administrator:

.\Outil-Diagnostic-VM.ps1

In the GUI:

Check the desired diagnostics.

Fill in any required input (IP, port, AD user).

Click "Lancer l'audit" (Run Audit) to start.

Review results in the output box.

Output : 

A progress bar shows the audit’s completion status.

Each selected test returns a detailed output.

Errors are handled and displayed accordingly.
