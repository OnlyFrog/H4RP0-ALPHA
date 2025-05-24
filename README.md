# H4RP0-ALPHA
First version of H4RP0, a project of hack on LAN.        !!Alpha Version!!





# H4RP0 - Outil avancé d’attaque réseau et d’analyse de vulnérabilités

H4RP0 est un outil en ligne de commande (CLI) développé en Python, conçu pour automatiser et simplifier plusieurs types d’attaques réseau et de scans de sécurité.  
Il cible principalement les environnements de tests d’intrusion (pentesting) et les professionnels de la cybersécurité souhaitant disposer d’un outil multifonction facile à utiliser.

---

## Table des matières

- [Fonctionnalités principales](#fonctionnalités-principales)  
- [Installation](#installation)  
- [Prérequis](#prérequis)  
- [Utilisation détaillée](#utilisation-détaillée)  
- [Architecture du projet](#architecture-du-projet)  
- [Sécurité et éthique](#sécurité-et-éthique)  
- [FAQ](#faq)  
- [Contribuer](#contribuer)  
- [Licence](#licence)  

---

## Fonctionnalités principales

- **ARP Spoofing** : Permet de lancer une attaque Man-in-the-Middle en usurpant l’adresse MAC d’un routeur ou d’un hôte ciblé.  
- **Revolver** : Enchaîne plusieurs phases d’attaque (spoofing, sniffing, traceroute furtif, DNS spoof, etc.) pour des scénarios avancés.  
- **Scan de vulnérabilités** : Utilisation de Nmap pour détecter les failles et services exposés sur une cible spécifique.  
- **NetScan** : Scanner passif et actif du réseau local pour détecter tous les appareils connectés, avec leurs IP, MAC et noms d’hôtes.  
- **Interface CLI intuitive** : Commandes simples, prompt interactif, et aide intégrée.

---

## Installation

### Pré-requis système

- Python 3.8+  
- Droits administrateur/root (requis pour sniffing et spoofing réseau)  
- Nmap installé sur la machine (disponible sur [nmap.org](https://nmap.org))

### Installation des dépendances

Cloner le dépôt :

```bash
git clone https://github.com/ton-utilisateur/h4rp0.git
cd h4rp0
