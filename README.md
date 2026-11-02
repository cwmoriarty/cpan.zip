# cpan.zip — Synology DSM Community Package Repository 🌳📦

Welcome to the **SynDirStat** community package repository hosted on GitHub Pages by [Chris Moriarty (cwmoriarty)](https://github.com/cwmoriarty).

This repository distributes **SynDirStat**, a free, open-source native Synology DSM 7 storage visualization and historical analysis application inspired by WinDirStat, WizTree, SequoiaView, and SpaceSniffer.

---

## 🚀 Adding this Repository to Synology DSM Package Center

You can install SynDirStat and receive automatic updates directly through DSM Package Center:

1. Open your Synology DSM web desktop (`http://your-nas-ip:5000`).
2. Open **Package Center**.
3. Click **Settings** (top right).
4. Select the **Package Sources** tab and click **Add**.
5. Fill in the fields:
   - **Name**: `SynDirStat Community`
   - **Location**: `https://cwmoriarty.github.io/cpan.zip/`
6. Click **OK**.
7. In Package Center, navigate to the **Community** tab and click **Install** next to **SynDirStat**.

---

## 📦 Packages Available

| Package | Version | Supported Architectures | Download |
|---|---|---|---|
| **SynDirStat (x86_64)** | 1.0.0-0001 | Intel & AMD 64-bit (Plus, XS, FS series) | [Download SPK](packages/syndirstat/syn-dirstat-x86_64-1.0.0.spk) |
| **SynDirStat (ARM64)** | 1.0.0-0001 | Realtek RTD1296, RTD1619b and ARM64 series | [Download SPK](packages/syndirstat/syn-dirstat-arm64-1.0.0.spk) |
| **SynDirStat (Universal)** | 1.0.0-0001 | All DSM 7.0+ compliant architectures | [Download SPK](packages/syndirstat/syn-dirstat-all-1.0.0.spk) |

---

## 📂 Repository Structure

- [`syndirstat/`](syndirstat/): Complete source code for the Go backend, React + TypeScript frontend, D3 treemap, and SPK packaging.
- [`packages/syndirstat/`](packages/syndirstat/): Distributable Synology `.spk` package files.
- [`repository/`](repository/): Package Center JSON feed (`packages.json`) and catalog index.
- [`index.html`](index.html): GitHub Pages landing page.
- [`.github/workflows/`](.github/workflows/): Automated CI/CD pipelines for testing, SPK building, releases, and GitHub Pages deployment.

---

## 📄 License

MIT License. Copyright (c) 2026 Chris Moriarty.
