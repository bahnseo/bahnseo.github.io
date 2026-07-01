# 개인정보 처리방침 (Privacy Policy)

본 개인정보 처리방침은 '결제타임 (PayTime)'(이하 '앱')이 사용자의 정보를 어떻게 다루는지 설명합니다.

## 1. 개인정보의 수집 및 이용 목적
'앱'은 원칙적으로 사용자의 개인 식별 정보를 수집하거나 개발자의 서버로 전송하지 않습니다. 사용자가 입력하는 모든 데이터(구독 항목, 결제 금액, 결제 수단, 메모 등)는 사용자의 기기 내부에만 로컬 데이터베이스(Hive) 형식으로 저장됩니다.
단, 무료 사용자를 위한 구글 애드몹(AdMob) 광고 송출 및 사용자가 직접 선택하여 사용하는 구글 드라이브(Google Drive) 클라우드 백업 기능 연동 과정에서 제3자(Third-party) 서비스에 의한 정보 처리가 발생할 수 있습니다.

## 2. 수집 및 처리하는 정보 항목
사용자 직접 입력 데이터 (로컬 저장): 사용자가 등록한 구독 서비스명, 금액, 결제 수단, 결제 예정일 등은 오직 기기 내부에서 관리 용도로만 저장 및 사용됩니다.
제3자 서비스에 의한 자동 수집 및 연동:
    구글 애드몹 (Google AdMob): 무료 버전 내 배너 광고 노출을 위해 사용자의 기기 식별자(광고 ID - ADID/IDFA), IP 주소, 대략적인 위치 정보, 광고 상호작용 데이터 등이 구글(Google)에 의해 수집 및 처리될 수 있습니다. 이 정보는 개인의 식별이 불가능한 형태로 광고 최적화 및 부정 방지에 활용됩니다.
    구글 드라이브 백업 (Google Sign-In & Google Drive API): 사용자가 설정에서 클라우드 백업을 수동 또는 자동으로 활성화하는 경우, 구글 로그인을 통해 사용자의 개인 구글 드라이브 내 `PayTime_Backups` 폴더에 암호화된 백업 파일(`.bck`)을 저장합니다. 개발자는 사용자의 구글 계정 자격 증명이나 드라이브 내 파일에 절대 접근할 수 없으며, 모든 업로드 및 복구는 사용자 기기에서 직접 구글 API를 통해 안전하게 수행됩니다.

## 3. 데이터 보안 및 보호 조치
'앱'은 사용자의 소중한 데이터를 보호하기 위해 다음과 같은 보안 기능을 제공합니다.
앱 잠금 (App Lock): 4자리 PIN 번호 및 생체 인식(지문/얼굴)을 통해 앱 접근을 제어하여 제3자로부터 개인적인 지출 내역을 보호할 수 있습니다.
백업 데이터 암호화 (AES-256): 사용자가 생성하는 모든 백업 파일(`.bck`)은 사용자가 설정한 백업 비밀번호를 기반으로 AES-256 표준 알고리즘을 통해 강력하게 암호화됩니다. 암호키가 없이는 파일을 열람하거나 복구할 수 없습니다.

## 4. 개인정보의 보유 및 파기
모든 로컬 데이터는 사용자의 기기에 저장되므로, 사용자가 '앱'을 삭제하면 모든 데이터는 즉시 영구적으로 파기됩니다. 사용자가 구글 드라이브에 올린 백업 파일은 사용자가 직접 자신의 구글 드라이브에서 삭제하여 파기할 수 있습니다.

## 5. 앱 권한 사용 안내
'앱'은 원활한 기능 제공을 위해 다음의 기기 권한을 요청합니다.
알림 (POST_NOTIFICATIONS): 구독 결제일 및 기한/쿠폰 만료일을 사용자에게 알리기 위해 사용됩니다.
생체 인식 (USE_BIOMETRIC / USE_FINGERPRINT): 앱 잠금 해제 시 생체 인증(지문/Face ID) 수단을 제공하기 위해 사용됩니다.
저장소/파일 접근 (필요 시): 로컬 백업 파일을 기기에 저장하거나 기존 백업 파일을 불러오기 위해 사용됩니다.
인터넷 (INTERNET): 구글 애드몹 배너 광고 로드, 구글 로그인 및 구글 드라이브 클라우드 백업 파일 전송을 위해 사용됩니다.

## 6. 제3자 제공 및 위탁에 대한 동의
'앱'은 사용자 데이터를 판매하거나 외부 서비스에 무단 제공하지 않습니다. 다만, 서비스 제공을 위해 아래의 신뢰할 수 있는 제3자 SDK 및 서비스를 포함하고 있으며, 각 서비스의 개인정보 처리방침은 아래 링크에서 확인하실 수 있습니다.
Google Play Services: [https://policies.google.com/privacy](https://policies.google.com/privacy)
Google AdMob: [https://support.google.com/admob/answer/6128543](https://support.google.com/admob/answer/6128543)

## 7. 문의 및 개인정보 보호담당자
'앱' 사용 중 개인정보 보호에 관하여 문의사항이 있으시면 아래 이메일로 연락해 주시기 바랍니다.
담당자 이메일: ietersacrum@gmail.com

## 8. 방침 변경 시 공지
본 방침은 법령 또는 서비스의 변경에 따라 수정될 수 있으며, 개정 사항은 앱 마켓 또는 앱 내 공지를 통해 투명하게 안내합니다.
시행일: 2026년 7월 1일 (개정)

---

# Privacy Policy (English)

This Privacy Policy explains how 'PayTime' (hereinafter referred to as 'the App') handles your information.

## 1. Purpose of Collection and Use of Personal Information
In principle, the App does not collect or transmit any personally identifiable information to external developer servers. All data (subscription items, payment amounts, payment methods, memos, etc.) entered by the user is stored locally on the user's device in a local database format (Hive).
However, information may be processed by third-party services in the process of serving ads through Google AdMob for free users, and integrating Google Drive cloud backup as chosen by the user.

## 2. Information Items Collected and Processed
User Input Data (Local Storage): Subscription names, prices, payment methods, and scheduled dates entered by the user are stored and used strictly for management purposes within the device.
Automatic Collection and Integration by Third Parties:
    Google AdMob: To serve banner ads in the free version, device identifiers (Advertising ID - ADID/IDFA), IP address, coarse location information, and ad interaction data may be collected and processed by Google. This information is processed in a non-personally identifiable form for ad optimization and fraud prevention.
    Google Drive Backup (Google Sign-In & Google Drive API): When the user enables the cloud backup feature manually or automatically in the settings, the App authenticates via Google Sign-In and uploads encrypted backup files (`.bck`) to a folder named `PayTime_Backups` on the user's personal Google Drive. The developer has absolutely no access to the user's Google account credentials or the files in Google Drive. All upload and restore operations are performed directly via the Google API from the user's device.

## 3. Data Security and Protection
The App provides strong security features to protect your valuable data:
App Lock: You can control access to the App and protect your spending privacy through a 4-digit PIN and biometrics (Fingerprint/Face).
Backup Data Encryption (AES-256): All backup files (`.bck`) created by the user are strongly encrypted using the AES-256 standard algorithm based on a user-defined backup password. The backup content cannot be decrypted or restored without the password.

## 4. Retention and Destruction of Personal Information
All local data is stored on the user's device. Therefore, all data is immediately and permanently destroyed when the user deletes the App. Backup files uploaded to Google Drive can be deleted and destroyed by the user directly from their Google Drive.

## 5. App Permissions Usage
The App requests the following device permissions to provide its features:
Notifications (POST_NOTIFICATIONS): Used for alerting users about payment dates and deadlines.
Biometrics (USE_BIOMETRIC / USE_FINGERPRINT): Used to provide biometric authentication (Fingerprint/Face ID) for unlocking the App.
Storage and File Access (if applicable): Used for saving local backup files on the device or restoring data from existing backups.
Internet (INTERNET): Used for loading Google AdMob banner ads, Google Sign-in, and transmitting cloud backup files to Google Drive.

## 6. Third-Party Disclosure and Consents
The App does not sell or unauthorizedly share user data with third parties. However, it integrates the following trusted third-party SDKs and services. You can review their privacy policies via the links below:
Google Play Services: [https://policies.google.com/privacy](https://policies.google.com/privacy)
Google AdMob: [https://support.google.com/admob/answer/6128543](https://support.google.com/admob/answer/6128543)

## 7. Contact and Privacy Officer
If you have any inquiries regarding privacy while using the App, please contact us at:
Contact Email: ietersacrum@gmail.com

## 8. Changes to the Policy
This policy may be updated due to changes in laws or services. Changes will be announced on the App Store or within the App.
Effective Date: July 1, 2026 (Revised)