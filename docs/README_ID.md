[English](README.md) | [Español](README_ES.md) | [简体中文](README_CN.md) | [繁體中文](README_TW.md) | [日本語](README_JP.md) | [한국어](README_KR.md) | [Polski](README_PL.md) | [Português (Brasil)](README_PT-BR.md) | [Türkçe](README_TR.md) | [Русский](README_RU.md) | [Tiếng Việt](README_VI.md) | **Indonesia** | [עברית](README_IW.md) | [हिंदी](README_IN.md) | [Italiano](README_IT.md)

# KernelSU

<img src="https://kernelsu.org/logo.png" style="width: 96px;" alt="logo">

Solusi root berbasis Kernel untuk perangkat Android.

[![Latest Release](https://img.shields.io/github/v/release/tiann/KernelSU?label=Release&logo=github)](https://github.com/tiann/KernelSU/releases/latest)
[![Weblate](https://img.shields.io/badge/Localization-Weblate-teal?logo=weblate)](https://hosted.weblate.org/engage/kernelsu)
[![Channel](https://img.shields.io/badge/Follow-Telegram-blue.svg?logo=telegram)](https://t.me/KernelSU)
[![License: GPL v2](https://img.shields.io/badge/License-GPL%20v2-orange.svg?logo=gnu)](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)
[![GitHub License](https://img.shields.io/github/license/tiann/KernelSU?logo=gnu)](/LICENSE)

## Fitur

1. Manajemen akses root dan `su` berbasis kernel.
2. Sistem modul berdasarkan [OverlayFS](https://en.wikipedia.org/wiki/OverlayFS).
3. [App profile](https://kernelsu.org/guide/app-profile.html): Kunci daya root di dalam sangkar.

## Status Kompatibilitas

KernelSU secara resmi mendukung perangkat Android GKI 2.0 (dengan kernel 5.10+), kernel lama (4.14+) juga kompatibel, tetapi Anda perlu membuat kernel sendiri.

WSA, ChromeOS, dan Android berbasis wadah juga dapat bekerja dengan KernelSU terintegrasi.

Dan ABI yang didukung saat ini adalah: `arm64-v8a` dan `x86_64`

## Penggunaan

- [Petunjuk Instalasi](https://kernelsu.org/id_ID/guide/installation.html)
- [Bagaimana cara membuat?](https://kernelsu.org/id_ID/guide/how-to-build.html)
- [Situs Web Resmi](https://kernelsu.org/id_ID/)

## Terjemahan

Untuk menerjemahkan KernelSU ke dalam bahasa Anda atau menyempurnakan terjemahan yang sudah ada, harap gunakan [Weblat](https://hosted.weblate.org/engage/kernelsu/).

## Diskusi

- Telegram: [@KernelSU](https://t.me/KernelSU)

## Lisensi

- File di bawah direktori `kernel` adalah [GPL-2-only](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html).
- Semua bagian lain kecuali direktori `kernel` adalah [GPL-3.0-or-later](https://www.gnu.org/licenses/gpl-3.0.html).

## Kredit

- [Kernel-Assisted Superuser](https://git.zx2c4.com/kernel-assisted-superuser/about/): Ide KernelSU.
- [Magisk](https://github.com/topjohnwu/Magisk): Alat root yang ampuh.
- [genuine](https://github.com/brevent/genuine/): Validasi tanda tangan APK v2.
- [Diamorphine](https://github.com/m0nad/Diamorphine): Beberapa keterampilan rootkit.
