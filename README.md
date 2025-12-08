# KeyVault

<p align="center">
  <img src="https://github.com/user-attachments/assets/c8e547fd-922e-4b96-982f-1d46855b0826" alt="KeyVault Icon" width="128" height="128">
</p>


<p align="center">
  <b>Secure, Modern, and Local-First License Manager for macOS</b>
  <br>
  macOS를 위한 안전하고 현대적인 로컬 우선 라이선스 매니저
</p>

<p align="center">
  <a href="#english">English</a> | <a href="#korean">한국어</a>
</p>

---
# 🔐 KeyVault for macOS

[English](#english) | [한국어](#korean)

---

<div id="english"></div>
## 🇺🇸 English

**The Ultimate License Manager for Mac Users**

KeyVault is not just a notepad. It is a native macOS application designed to manage software licenses, subscription details, and serial keys in the most beautiful and secure way. Experience the modern 'Crystal Aurora' glassmorphism design and powerful automation features.

### ✨ Key Features

#### 1. 🪄 Smart Drag & Drop
*   **Instant Recognition**: Simply drag and drop `.app` files into KeyVault. No typing required.
*   **Auto-Extraction**: Automatically extracts the app's **Name**, **Version**, **Publisher**, and **High-Res Icon**.
*   **Smart Icon Compression**: Extracted icons are automatically optimized (PNG) to save storage space.

<p align="center">
<img src="https://github.com/user-attachments/assets/42888938-7090-479a-b806-ac2d76696d7a" alt="keyvault-add">
</p>

#### 2. 🛡️ Bank-Grade Security
*   **Touch ID Support**: Unlock in 0.1 seconds using your fingerprint (Touch ID). No need to type passwords every time.
*   **Secure Enclave**: All data is encrypted and protected, accessible only by you.
*   **Master Password**: Provides dual security with a master password in case biometric authentication is unavailable.

<p align="center">
<img width="712" height="735" alt="keyvault-touchid_login" src="https://github.com/user-attachments/assets/c793bb7d-8a7a-4b56-a71d-80f94a083864" />
</p>

#### 3. ☁️ iCloud Sync & Freedom
*   **Seamless Sync**: Real-time synchronization of license data across all your Macs (iMac, MacBook) via iCloud Drive.
*   **Local First**: Works perfectly without internet. Data is stored locally and syncs automatically when connected.
*   **No Lock-in**: Export and backup your data anytime in **JSON**, **CSV** (Excel), or **ZIP** formats.

<p align="center">
<img width="712" height="700" alt="keyvault-rxqv" src="https://github.com/user-attachments/assets/9d2fa3f5-0808-448f-b343-62957234eeeb" />
</p>

#### 4. 💎 Crystal Aurora Design
*   **Visual Excellence**: The 'Crystal Aurora' theme (v1.3.0) offers a stunning visual experience with moving gradient backgrounds and glassmorphism effects.
*   **Fluid Animations**: Modern UI with smooth hover effects and floating card designs.
*   **Dark/Light Mode**: Looks perfect in both Dark and Light modes.

<p align="center">
<img src="https://github.com/user-attachments/assets/e490a04e-c5fc-460f-b651-51fc39009a69" width="48%" />
<img src="https://github.com/user-attachments/assets/0c4c6f8d-f324-4456-9e2c-2b36153c7d2e" width="48%" />
</p>

#### 5. 📊 Dashboard & Smart Management
*   **Visual Analytics**: Visualize total license value, category distribution, and top publishers with beautiful charts.
*   **Billing Cycles**: Manage monthly/yearly subscriptions and track renewal cycles at a glance.
*   **Smart Folders**: Automatically categorizes items like 'Expiring Soon', 'Recently Added', and 'Subscriptions'.
*   **Multi-Currency**: Supports global currencies (USD, EUR, KRW, etc.).

<p align="center">
<img src="https://github.com/user-attachments/assets/946bd0ce-5f8d-4401-89d7-106ba439c96f" width="40%" />
</p>

#### 6. 🧑‍💻 Developer Features
*   **Homebrew Integration**: Automatically generates `brew install --cask <app>` commands based on registered app names. Useful for re-setting up your Mac.
*   **Markdown Notes**: Keep clean records using Markdown syntax (Headers, Lists, Code Blocks) in your notes.

<p align="center">
<img width="493" height="101" alt="keyvault-autobrew" src="https://github.com/user-attachments/assets/dace7ffc-ea41-4143-8473-60cb2a8f47a1" />
</p>

<p align="center">
<img width="450" height="857" alt="keyvault-mulf" src="https://github.com/user-attachments/assets/5a376f81-d42d-42f8-9f36-7339ff90ef78" />
</p>

### 📥 Installation

1.  Download the latest `KeyVault.app.zip` from the [Releases](https://github.com/hjm79/keyvault-xcode/releases) page.
2.  Unzip the file and move `KeyVault.app` to your `Applications` folder.
3.  **Important**: Since this app is not signed with a paid Apple Developer ID, you must run the following command in Terminal before opening it for the first time:
    ```
    sudo xattr -r -d com.apple.quarantine /Applications/KeyVault.app
    ```
4.  Open KeyVault and enjoy!

---

<div id="korean"></div>
## 🇰🇷 한국어

**macOS를 위한 최고의 프리미엄 라이선스 매니저**

KeyVault는 단순한 메모장이 아닙니다. 소프트웨어 라이선스, 구독 정보, 시리얼 키를 가장 아름답고 안전하게 관리할 수 있는 macOS 전용 네이티브 앱입니다. 'Crystal Aurora' 테마가 적용된 현대적인 글래스모피즘 디자인과 강력한 자동화 기능을 경험해 보세요.

### ✨ 주요 기능

#### 1. 🪄 스마트 드래그 앤 드롭 (Smart Drag & Drop)
*   **Instant Recognition**: `.app` 파일을 KeyVault로 드래그 앤 드롭하기만 하세요. 타이핑할 필요가 없습니다.
*   **Auto-Extraction**: 앱의 **이름**, **버전**, **퍼블리셔**, **고해상도 아이콘**까지 모든 정보를 자동으로 추출하여 입력을 완료해 줍니다.
*   **Smart Icon Compression**: 추출된 아이콘은 자동으로 최적화(PNG)되어 저장 용량을 절약합니다.

<p align="center">
<img src="https://github.com/user-attachments/assets/42888938-7090-479a-b806-ac2d76696d7a" alt="keyvault-add">
</p>

#### 2. 🛡️ 강력한 보안 (Bank-Grade Security)
*   **Touch ID Support**: 매번 비밀번호를 입력할 필요 없이, 지문 인식(Touch ID)으로 0.1초 만에 잠금을 해제하세요.
*   **Secure Enclave**: 모든 데이터는 안전하게 암호화(Encrypted)되어 보호되며, 오직 당신만이 접근할 수 있습니다.
*   **Master Password**: 생체 인증을 사용할 수 없을 때를 대비한 마스터 비밀번호로 이중 보안을 제공합니다.

<p align="center">
<img width="712" height="735" alt="keyvault-touchid_login" src="https://github.com/user-attachments/assets/c793bb7d-8a7a-4b56-a71d-80f94a083864" />
</p>

#### 3. ☁️ iCloud 동기화 (iCloud Sync & Freedom)
*   **Seamless Sync**: iCloud Drive를 통해 내 모든 Mac(iMac, MacBook)에서 라이선스 데이터가 실시간으로 동기화됩니다.
*   **Local First**: 인터넷이 없어도 괜찮습니다. 데이터는 기본적으로 로컬에 저장되며 연결 시 자동으로 동기화됩니다.
*   **No Lock-in**: 언제든 데이터를 **JSON**, **CSV** (엑셀), **ZIP** 형식으로 내보내고 백업할 수 있습니다.

<p align="center">
<img width="712" height="700" alt="keyvault-rxqv" src="https://github.com/user-attachments/assets/9d2fa3f5-0808-448f-b343-62957234eeeb" />
</p>

#### 4. 💎 프리미엄 디자인 (Crystal Aurora Design)
*   **Visual Excellence**: v1.3.0에 적용된 'Crystal Aurora' 테마는 움직이는 그라데이션 배경과 글래스모피즘(Glassmorphism) 효과로 환상적인 시각 경험을 제공합니다.
*   **Fluid Animations**: 부드러운 호버 효과와 카드가 공중에 떠 있는 듯한 모던한 UI를 적용했습니다.
*   **Dark/Light Mode**: 다크 모드와 라이트 모드 모두에서 완벽하게 아름답습니다.

<p align="center">
<img src="https://github.com/user-attachments/assets/e490a04e-c5fc-460f-b651-51fc39009a69" width="48%" />
<img src="https://github.com/user-attachments/assets/0c4c6f8d-f324-4456-9e2c-2b36153c7d2e" width="48%" />
</p>

#### 5. 📊 대시보드 및 스마트 관리 (Dashboard & Smart Management)
*   **Visual Analytics**: 보유한 라이선스의 총 가치, 카테고리별 분포, 상위 퍼블리셔 등을 아름다운 차트로 시각화해 줍니다.
*   **Billing Cycles**: 매달/매년 나가는 구독료를 관리하세요. 결제 갱신 주기를 한눈에 파악할 수 있습니다.
*   **Smart Folders**: '만료 임박', '최근 추가됨', '구독 중'인 항목을 자동으로 분류해 줍니다.
*   **Multi-Currency**: KRW, USD, EUR 등 전 세계 통화를 지원하고 환율에 따른 가치를 (추후 업데이트 예정) 통합 관리합니다.

<p align="center">
<img src="https://github.com/user-attachments/assets/946bd0ce-5f8d-4401-89d7-106ba439c96f" width="40%" />
</p>

#### 6. 🧑‍💻 개발자 친화 기능 (Developer Features)
*   **Homebrew Integration**: 등록된 앱 이름을 기반으로 `brew install --cask <app>` 명령어를 자동으로 생성해 주어, 맥을 포맷하고 다시 세팅할 때 유용합니다.
*   **Markdown Notes**: 메모장에 마크다운 문법(헤더, 리스트, 코드 블럭)을 사용하여 깔끔하게 기록하세요.

<p align="center">
<img width="493" height="101" alt="keyvault-autobrew" src="https://github.com/user-attachments/assets/dace7ffc-ea41-4143-8473-60cb2a8f47a1" />
</p>

<p align="center">
<img width="450" height="857" alt="keyvault-mulf" src="https://github.com/user-attachments/assets/5a376f81-d42d-42f8-9f36-7339ff90ef78" />
</p>

### 📥 설치 방법 (Installation)

1.  [Releases](https://github.com/hjm79/keyvault-xcode/releases) 페이지에서 최신 `KeyVault.app.zip`을 다운로드합니다.
2.  압축을 풀고 `KeyVault.app`을 `응용 프로그램 (Applications)` 폴더로 이동합니다.
3.  **중요**: 이 앱은 Apple 개발자 서명이 되어 있지 않으므로, 최초 실행 전 터미널(Terminal)에서 아래 명령어를 실행해야 합니다:
    ```
    sudo xattr -r -d com.apple.quarantine /Applications/KeyVault.app
    ```
4.  앱을 실행하고 마스터 비밀번호를 설정하여 시작하세요!


---
*Note: This repository is for releases and issue tracking only. The source code is private.*
