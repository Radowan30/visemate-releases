<p align="center">
  <a href="https://visemate.app">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset=".github/assets/visemate-logo-dark.png">
      <img src=".github/assets/visemate-logo.png" alt="Visemate, supporting your academic journey" width="360">
    </picture>
  </a>
</p>

<h3 align="center">Visemate for Android</h3>

<p align="center">
  Meetings, tasks, milestones and progress, for research supervisors and their students.
</p>

<p align="center">
  <a href="https://github.com/Radowan30/visemate-releases/releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/Radowan30/visemate-releases?label=latest%20release&color=005cb2"></a>
  <img alt="Android 7.0 or later" src="https://img.shields.io/badge/Android-7.0%2B-005cb2?logo=android&logoColor=white">
  <a href="https://visemate.app"><img alt="Also in your browser at visemate.app" src="https://img.shields.io/badge/web-visemate.app-005cb2"></a>
</p>

<p align="center">
  <a href="https://github.com/Radowan30/visemate-releases/releases/latest/download/visemate.apk"><strong>Download the latest APK</strong></a>
  &nbsp;·&nbsp;
  <a href="https://visemate.app/download">visemate.app/download</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/Radowan30/visemate-releases/releases">All releases</a>
</p>

---

This repository is where the Visemate Android app is published. Each [release](https://github.com/Radowan30/visemate-releases/releases)
carries one file, `visemate.apk`, with its SHA-256 checksum and the fingerprint of the key it is signed with. The
source code is private and is not published here.

## Install

You need a phone or tablet with **Android 7.0 or later**.

1. On your phone, open **[visemate.app/download](https://visemate.app/download)** and tap **Download for Android**,
   or download `visemate.apk` from the [latest release](https://github.com/Radowan30/visemate-releases/releases/latest).
   Your browser may warn that the file could be harmful. It says that about every app that does not come from
   Google Play. Choose **Download anyway**.
2. Open the file when it has downloaded. If your phone asks, allow installing from that source, then go back and
   open the file again.
3. Tap **Install**. Google Play Protect may recommend scanning the app, because it has not seen it before: tap
   **Scan app**, then **Install**.
4. Open Visemate and sign in, or create your account.

Not on Android? Visemate works in any modern browser at **[visemate.app](https://visemate.app)**, on a computer,
an iPhone or an iPad.

## Updates

Visemate tells you when an update is needed. Tap **Update now**: the new version downloads in your browser. Open it
and tap **Update**, and let Google Play Protect scan it if it offers to. You stay signed in, and nothing you have
recorded is lost.

Android installs an update only when it is signed with the same key as the app already on your phone. A copy that
has been tampered with cannot replace Visemate.

## Check your download

Get Visemate only from this repository, from [visemate.app/download](https://visemate.app/download), or from the
app's own **Update now** button. A copy forwarded through a chat app could have been changed.

To be certain, compare the file's SHA-256 checksum with the one in the release notes:

| On | Run |
|---|---|
| Windows (PowerShell) | `Get-FileHash .\visemate.apk -Algorithm SHA256` |
| macOS | `shasum -a 256 visemate.apk` |
| Linux | `sha256sum visemate.apk` |

Developers can also check the signature with the Android SDK's `apksigner verify --print-certs visemate.apk`. The
certificate's SHA-256 digest must match the fingerprint in the release notes.

## Privacy

Visemate's servers and database are in Singapore. What the app records, why, and who can see it is set out in the
privacy notice you are shown before you create an account, in English and Bahasa Malaysia. Downloading the app from
GitHub shares nothing with Visemate; GitHub's own [privacy statement](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement)
covers the download itself.

## Help and security

- **Help with your account:** ask your supervisor or your Visemate administrator. Issues are switched off in this
  repository, so that nobody posts details about themselves or their students in public.
- **A security problem:** report it privately, as described in [SECURITY.md](SECURITY.md).
