# ArgentForge Releases & Open Ecosystem

Welcome to the official public distribution hub for **[Booksmith Studio](https://argentforge.xyz)** and the **DarkQuill Reader**.

---

## 📢 Beta Release v0.8.0-beta.2 is Live

Multi-platform desktop and mobile release binaries are available for **macOS (Universal Apple Silicon & Intel)**, **Windows 10/11 (EXE & MSI)**, **Linux (AppImage, DEB, RPM)**, and **Android (APK & AAB)**.

Download verified installers directly from the **[Releases Tab](https://github.com/argentforge/releases/releases)** or from the official download portal at **[argentforge.xyz](https://argentforge.xyz)**.

---

## 🖥️ Studio Showcase

### 1. The Writing Studio
Focus-driven manuscript drafting with a hierarchical binder (Front Matter, Chapters, Scenes, Back Matter), real-time scene context (writing goals, active cast references, intention notes), and local document state powered by the RuneCore engine.

![Booksmith Writing Studio](screenshots/writing-studio.png)

---

### 2. Print & PDF Typesetting Studio
Live interactive book-block preview with realistic pagination, edition pre-flight readiness checks, cover artwork management, and typographical styling presets (Garamond, Cinzel, and custom themes).

![Booksmith Publication Studio](screenshots/publication-studio.png)

---

### 3. Serialized Web Novel Studio
Episode-based serialization workflow for digital fiction and web platforms. Features one-click chapter-to-episode linking, release schedule planning (Draft, Scheduled, Public Release), and word count granularity.

![Booksmith Web Novel Serialization Studio](screenshots/webNovelPublication.png)

---

### 4. Gamebook & Interactive Story Studio
Branching narrative graph canvas, player state tracking (variables, conditions, counters), and situation authoring for interactive storytellers. Export encrypted living novels (`.gyjpkg`) readable directly in the companion DarkQuill mobile app.

---

## 📦 Verified Installer Matrix (v0.8.0-beta.2)

| Platform | Format | Recommended Target | Direct Download |
| :--- | :--- | :--- | :--- |
| 🍏 **macOS** | **Universal DMG** (`.dmg`) | macOS 12.0+ (Apple Silicon M1–M4 & Intel x86_64) | [Booksmith_0.8.0_universal.dmg](https://github.com/argentforge/releases/releases/download/v0.8.0-beta.2/Booksmith_0.8.0_universal.dmg) |
| 🍏 **macOS** | **Standalone Archive** (`.tar.gz`) | Standalone portable `.app` bundle | [Booksmith_universal.app.tar.gz](https://github.com/argentforge/releases/releases/download/v0.8.0-beta.2/Booksmith_universal.app.tar.gz) |
| 🪟 **Windows** | **Setup Installer** (`.exe`) | Windows 10 & 11 (64-bit) | [Booksmith_0.8.0_x64-setup.exe](https://github.com/argentforge/releases/releases/download/v0.8.0-beta.2/Booksmith_0.8.0_x64-setup.exe) |
| 🪟 **Windows** | **Enterprise Package** (`.msi`) | Enterprise & group policy deployment | [Booksmith_0.8.0_x64_en-US.msi](https://github.com/argentforge/releases/releases/download/v0.8.0-beta.2/Booksmith_0.8.0_x64_en-US.msi) |
| 🐧 **Linux** | **AppImage** (`.AppImage`) | Universal Linux distributions (Ubuntu, Fedora, Arch) | [Booksmith_0.8.0_amd64.AppImage](https://github.com/argentforge/releases/releases/download/v0.8.0-beta.2/Booksmith_0.8.0_amd64.AppImage) |
| 🐧 **Linux** | **Debian Package** (`.deb`) | Debian, Ubuntu, Linux Mint | [Booksmith_0.8.0_amd64.deb](https://github.com/argentforge/releases/releases/download/v0.8.0-beta.2/Booksmith_0.8.0_amd64.deb) |
| 🐧 **Linux** | **RPM Package** (`.rpm`) | Fedora, Red Hat Enterprise Linux, openSUSE | [Booksmith-0.8.0-1.x86_64.rpm](https://github.com/argentforge/releases/releases/download/v0.8.0-beta.2/Booksmith-0.8.0-1.x86_64.rpm) |
| 🤖 **Android** | **Standalone APK** (`.apk`) | Android 6.0+ Phones & Tablets | [DarkQuill-Reader-release.apk](https://github.com/argentforge/releases/releases/download/v0.8.0-beta.2/DarkQuill-Reader-release.apk) |
| 🤖 **Android** | **Google Play Bundle** (`.aab`) | Play Store distribution package | [DarkQuill-Reader-release.aab](https://github.com/argentforge/releases/releases/download/v0.8.0-beta.2/DarkQuill-Reader-release.aab) |

---

## 🟢 Open-Source Core (`@argentforge/core`)
The foundational document domain of the ArgentForge ecosystem is open-source under the **Apache 2.0 License**:  
👉 **Repository**: [https://github.com/argentforge/core](https://github.com/argentforge/core)

This package contains the complete **`.gyj` Open Document Specification**, TypeScript data models (Chapters, Scenes, Binder Nodes, Front-Matter), JSON serializers, and schema validators. It guarantees that authors retain 100% data ownership over their manuscripts with zero vendor lock-in.

---

## 🗺️ Structured Roadmap
1. **Phase 1 (Active)**: Open `.gyj` Document Models & Schema Serializers ([@argentforge/core](https://github.com/argentforge/core)).
2. **Phase 2 (Active)**: Official Website codebase, documentation portal, and release distribution.
3. **Phase 3 (Active)**: Booksmith Desktop Application UI and DarkQuill reader evolution.

---

## 🛡️ License & Data Sovereignty
Booksmith and DarkQuill are distributed under the **ArgentForge Free Application License** — 100% Free for personal and commercial publishing with zero royalties, zero advertising, and zero telemetry. All documents are stored strictly on your local disk.

- **Official Website**: [https://argentforge.xyz](https://argentforge.xyz)
- **Bug Reports & Feedback**: [GitHub Issues Tracker](https://github.com/argentforge/releases/issues)
- **Contact**: `team@argentforge.xyz`
