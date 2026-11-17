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

## Explorer

| Domaine | Ce que l'on y trouve | Dossier |
| :--- | :--- | :--- |
| 🌐 **Réseau** | Analyse de captures, protocoles et configuration réseau | [Ouvrir Network](https://github.com/alex-beze/Module_Intro_Securite_2026-2027/tree/main/CARON/Root-Me.org/Network) |
| 🧩 **Web Server** | Requêtes HTTP, fichiers exposés et injection de commande | [Ouvrir Web Server](https://github.com/alex-beze/Module_Intro_Securite_2026-2027/tree/main/CARON/Root-Me.org/Web%20Server) |

```mermaid
flowchart LR
    A["Notes et captures"] --> B["Write-up Markdown"]
    B --> C["Archive ZIP chiffrée"]
    C --> D["Network"]
    C --> E["Web Server"]
    classDef source fill:#0d1931,stroke:#00bbd4,color:#ffffff;
    classDef archive fill:#1d1740,stroke:#9b7bff,color:#ffffff;
    class A,B source;
    class C,D,E archive;
```

<details>
<summary><strong>🌐 Voir les 6 write-ups Réseau</strong></summary>

| Challenge | Archive |
| :--- | :--- |
| [CISCO](https://www.root-me.org/fr/Challenges/Reseau/CISCO-mot-de-passe) | [Télécharger](Network/CARON_WU_CISCO.zip) |
| [ETHERNET - trame](https://www.root-me.org/fr/Challenges/Reseau/ETHERNET-trame) | [Télécharger](Network/CARON_WU_ETHERNET_TRAME.zip) |
| [FTP - Authentification](https://www.root-me.org/fr/Challenges/Reseau/FTP-Authentification) | [Télécharger](Network/CARON_WU_FTP_AUTHENTIFICATION.zip) |
| [IP - Time To Live](https://www.root-me.org/fr/Challenges/Reseau/IP-Time-To-Live) | [Télécharger](Network/CARON_WU_IP_TIME_TO_LIVE.zip) |
| [RIPv1 - no authentication](https://www.root-me.org/fr/Challenges/Reseau/RIPv1-no-authentication) | [Télécharger](Network/CARON_WU_RIPV1_NO_AUTHENTICATION.zip) |
| [TELNET - authentification](https://www.root-me.org/fr/Challenges/Reseau/TELNET-authentification) | [Télécharger](Network/CARON_WU_TELNET_AUTHENTIFICATION.zip) |

</details>

<details>
<summary><strong>🧩 Voir les 5 write-ups Web Server</strong></summary>

| Challenge | Archive |
| :--- | :--- |
| [Fichier de sauvegarde](https://www.root-me.org/fr/Challenges/Web-Serveur/Fichier-de-sauvegarde) | [Télécharger](Web%20Server/CARON_WU_WEB_SERVER_FICHIER_DE_SAUVEGARDE.zip) |
| [HTTP - Directory indexing](https://www.root-me.org/en/Challenges/Web-Server/HTTP-Directory-indexing) | [Télécharger](Web%20Server/CARON_WU_WEB_SERVER_HTTP_DIRECTORY_INDEXING.zip) |
| [HTTP - Headers](https://www.root-me.org/fr/Challenges/Web-Serveur/HTTP-Headers) | [Télécharger](Web%20Server/CARON_WU_WEB_SERVER_HTTP_HEADERS.zip) |
| [HTTP - POST](https://www.root-me.org/en/Challenges/Web-Server/HTTP-POST) | [Télécharger](Web%20Server/CARON_WU_WEB_SERVER_HTTP_POST.zip) |
| [PHP - Injection de commande](https://www.root-me.org/fr/Challenges/Web-Serveur/Injection-de-commande) | [Télécharger](Web%20Server/CARON_WU_WEB_SERVER_PHP_INJECTION_DE_COMMANDE.zip) |

</details>

---

Les solutions et les captures sont réunies dans des archives ZIP chiffrées. Le mot de passe est communiqué séparément. Le [suivi des challenges](../caron.md) regroupe Root-Me PRO et Root-Me.org.
