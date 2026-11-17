<p align="center">
  <img src="assets/network-web-banner.png" alt="Illustration d'un réseau et d'une application web" width="100%">
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/root-me-mark-white.svg">
    <source media="(prefers-color-scheme: light)" srcset="assets/root-me-mark-black.svg">
    <img src="assets/root-me-mark-black.svg" alt="Logo Root-Me" width="80">
  </picture>
</p>

<h1 align="center">Root-Me.org</h1>

<p align="center">
  <strong>Mes write-ups, classés par domaine.</strong><br>
  Des captures, une démarche et un résultat pour chaque challenge documenté.
</p>

<p align="center">
  <img alt="Réseau : 6 write-ups" src="https://img.shields.io/badge/R%C3%A9seau-6%20write--ups-00BBD4?style=for-the-badge">
  <img alt="Web Server : 5 write-ups" src="https://img.shields.io/badge/Web%20Server-5%20write--ups-7654D9?style=for-the-badge">
  <img alt="Archives chiffrées" src="https://img.shields.io/badge/Archives-ZIP%20AES--256-24324A?style=for-the-badge">
</p>

---

## Parcours des notions

Chaque branche regroupe les techniques rencontrées dans les write-ups. Les fiches plus bas donnent accès au challenge et à son archive.

```mermaid
flowchart TB
    R["Root-Me.org"] --> N["Réseau"]
    R --> W["Web Server"]
    N --> N1["Observer le trafic<br/>Ethernet · FTP · Telnet"]
    N --> N2["Comprendre le réseau<br/>TTL · RIPv1"]
    N --> N3["Lire une configuration<br/>Cisco"]
    W --> W1["Repérer des fichiers exposés<br/>Sauvegarde · Indexation"]
    W --> W2["Examiner les requêtes<br/>En-têtes · POST"]
    W --> W3["Tester une entrée<br/>Injection de commande"]
    classDef root fill:#0d1931,stroke:#ffffff,color:#ffffff;
    classDef network fill:#073642,stroke:#00bbd4,color:#ffffff;
    classDef web fill:#271942,stroke:#9b7bff,color:#ffffff;
    class R root;
    class N,N1,N2,N3 network;
    class W,W1,W2,W3 web;
```

## 🌐 Réseau

[Ouvrir le dossier Network](Network/)

> **CISCO**
> Décoder les valeurs d'une configuration Cisco.
> [Challenge Root-Me](https://www.root-me.org/fr/Challenges/Reseau/CISCO-mot-de-passe) · [Write-up chiffré](Network/CARON_WU_CISCO.zip)

> **ETHERNET - trame**
> Reconstituer une requête HTTP à partir d'une trame hexadécimale.
> [Challenge Root-Me](https://www.root-me.org/fr/Challenges/Reseau/ETHERNET-trame) · [Write-up chiffré](Network/CARON_WU_ETHERNET_TRAME.zip)

> **FTP - Authentification**
> Lire un échange FTP dans Wireshark et repérer l'authentification.
> [Challenge Root-Me](https://www.root-me.org/fr/Challenges/Reseau/FTP-Authentification) · [Write-up chiffré](Network/CARON_WU_FTP_AUTHENTIFICATION.zip)

> **IP - Time To Live**
> Distinguer le TTL des requêtes ICMP de celui des réponses.
> [Challenge Root-Me](https://www.root-me.org/fr/Challenges/Reseau/IP-Time-To-Live) · [Write-up chiffré](Network/CARON_WU_IP_TIME_TO_LIVE.zip)

> **RIPv1 - no authentication**
> Comprendre les annonces RIP et tester leur absence d'authentification.
> [Challenge Root-Me](https://www.root-me.org/fr/Challenges/Reseau/RIPv1-no-authentication) · [Write-up chiffré](Network/CARON_WU_RIPV1_NO_AUTHENTICATION.zip)

> **TELNET - authentification**
> Reconstituer une connexion Telnet à partir des paquets capturés.
> [Challenge Root-Me](https://www.root-me.org/fr/Challenges/Reseau/TELNET-authentification) · [Write-up chiffré](Network/CARON_WU_TELNET_AUTHENTIFICATION.zip)

## 🧩 Web Server

[Ouvrir le dossier Web Server](Web%20Server/)

> **Fichier de sauvegarde**
> Repérer un fichier de sauvegarde qui expose du code PHP.
> [Challenge Root-Me](https://www.root-me.org/fr/Challenges/Web-Serveur/Fichier-de-sauvegarde) · [Write-up chiffré](Web%20Server/CARON_WU_WEB_SERVER_FICHIER_DE_SAUVEGARDE.zip)

> **HTTP - Directory indexing**
> Explorer des répertoires dont l'index reste accessible.
> [Challenge Root-Me](https://www.root-me.org/en/Challenges/Web-Server/HTTP-Directory-indexing) · [Write-up chiffré](Web%20Server/CARON_WU_WEB_SERVER_HTTP_DIRECTORY_INDEXING.zip)

> **HTTP - Headers**
> Interpréter un en-tête HTTP inhabituel dans Burp.
> [Challenge Root-Me](https://www.root-me.org/fr/Challenges/Web-Serveur/HTTP-Headers) · [Write-up chiffré](Web%20Server/CARON_WU_WEB_SERVER_HTTP_HEADERS.zip)

> **HTTP - POST**
> Intercepter un formulaire POST et modifier la valeur envoyée.
> [Challenge Root-Me](https://www.root-me.org/en/Challenges/Web-Server/HTTP-POST) · [Write-up chiffré](Web%20Server/CARON_WU_WEB_SERVER_HTTP_POST.zip)

> **PHP - Injection de commande**
> Tester une injection de commande dans un formulaire de ping.
> [Challenge Root-Me](https://www.root-me.org/fr/Challenges/Web-Serveur/Injection-de-commande) · [Write-up chiffré](Web%20Server/CARON_WU_WEB_SERVER_PHP_INJECTION_DE_COMMANDE.zip)

---

Les solutions et les captures sont réunies dans des archives ZIP chiffrées. Le mot de passe est communiqué séparément. Le [suivi des challenges](../caron.md) regroupe Root-Me PRO et Root-Me.org.
