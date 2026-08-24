# 독서수첩 (ReadingTrail) 개인정보 처리방침 (Privacy Policy)

'독서수첩 (ReadingTrail)'(이하 '앱')은 사용자의 개인정보를 중요시하며, 「개인정보 보호법」 및 관련 법령을 준수합니다. 본 개인정보 처리방침은 앱이 사용자의 정보를 어떻게 다루는지 설명합니다.

---

### 1. 개인정보의 수집 및 이용 목적
* 본 앱은 사용자의 개인 식별 정보(이름, 전화번호, 주민등록번호 등)를 별도로 수집하거나 외부 중앙 서버로 전송하지 않습니다.
* 앱 내에서 작성되는 모든 데이터(도서 목록, 등장인물 정보, 인물 관계망 좌표, 독서 타임라인 메모, 설정 정보)는 사용자의 기기 내부 로컬 데이터베이스(SQLite/Drift)에만 안전하게 보관됩니다.

---

### 2. 수집하는 개인정보 항목 및 수집 방법
* **직접 수집:** 앱은 계정 가입이나 회원가입 절차가 없으며, 사용자의 개인정보를 직접 요구하거나 저장하지 않습니다.
* **외부 도서 검색 API:** 온라인 책 검색 기능 사용 시 사용자가 입력한 검색 키워드는 외부 서비스 API(알라딘, Google Books)로 전달되나, 이는 책 정보를 조회하기 위한 목적으로만 사용되며 검색 이력을 서버에 저장하지 않습니다.
* **AI 등장인물 분석 API:** AI 등장인물 자동 생성 기능 이용 시, 소설 제목/작가/줄거리 정보가 Google Gemini API로 전송되며, 이 정보는 오직 인물 분석 결과를 생성하기 위한 목적으로만 일회성으로 처리됩니다.
* **구글 드라이브 백업 서비스:** 사용자가 구글 드라이브 백업 기능을 직접 선택하여 활성화할 경우, 구글 OAuth 2.0 인증을 통해 사용자의 구글 계정 정보를 확인합니다. 백업 파일(`.bck`)은 사용자의 개인 구글 드라이브 내 앱 전용 보안 격리 공간(`appDataFolder`)에만 저장되며 개발자나 제3자가 접근할 수 없습니다.

---

### 3. 데이터 보유 및 파기 절차
* 모든 데이터는 사용자의 모바일 기기 및 사용자의 개인 구글 드라이브 계정에만 보관됩니다.
* 사용자가 앱을 삭제하거나, 앱 내 백업 데이터를 삭제하는 경우 해당 데이터는 즉시 영구적으로 파기됩니다.

---

### 4. 제3자 제공 및 위탁
* 앱은 사용자의 정보를 제3자에게 제공하거나 매매하지 않습니다.
* 외부 API 서비스(알라딘, Google Books, Gemini API, Google Drive API) 이용 시 각 서비스 제공업체의 개인정보 처리방침이 적용됩니다.

---

### 5. 앱 권한 사용 안내
앱은 정상적인 기능 제공을 위해 다음 최소 권한을 요청합니다:
* **인터넷 (`INTERNET`):** 온라인 도서 정보 검색, 외부 책 표지 이미지 로딩, AI 인물 분석 및 구글 드라이브 백업 전송을 위해 사용됩니다.
* **갤러리/미디어 접근 (`READ_EXTERNAL_STORAGE` / `READ_MEDIA_IMAGES`):** 사용자가 직접 소장 도서의 표지 이미지를 갤러리에서 선택하여 등록할 때만 사용됩니다.

---

### 6. 개인정보 보호책임자 및 문의처
앱 이용 중 개인정보와 관련된 문의사항이 있으시면 아래 연락처로 문의해 주시기 바랍니다.
* **이메일:** ietersacrum@gmail.com

---

**공고일자:** 2026년 8월 24일  
**시행일자:** 2026년 8월 24일

---

## Privacy Policy (English)

This Privacy Policy explains how **'ReadingTrail'** (hereinafter referred to as 'the App') handles your information.

### 1. Purpose of Collection and Use of Personal Information
The App does not collect or transmit any personally identifiable information to external servers. All data (book lists, character profiles, relationship maps, memos, and settings) is stored locally on your device in a local database (SQLite/Drift).

### 2. Information Handled by External Services
* **Book Search APIs:** Search terms are sent to external APIs (Aladin, Google Books) solely for retrieving book metadata.
* **AI Character Analysis:** Book title, author, and description are processed via Google Gemini API strictly to generate character relationship maps.
* **Google Drive Cloud Backup:** When enabled by the user, backup files (`.bck`) are uploaded exclusively to the user's private Google Drive AppData folder (`appDataFolder`). The developer has no access to your backup files.

### 3. Data Security and Destruction
All data resides on your device and your personal Google Drive account. Data is permanently deleted when the user uninstalls the App or clears app data.

### 4. Privacy Contact
For any privacy inquiries regarding the App, please contact:
* **Email:** ietersacrum@gmail.com

**Effective Date:** August 24, 2026
