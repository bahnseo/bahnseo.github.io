# 개인정보 처리방침 (Privacy Policy)

본 개인정보 처리방침은 'Keyrium Launcher (키리움 런처)'(이하 '앱')이 사용자의 개인정보 및 기기 데이터를 어떻게 취급하고 보호하는지 설명합니다. '앱'은 사용자의 프라이버시를 최우선으로 존중하며, 구글 플레이 개발자 프로그램 정책(Google Play Developer Program Policy)을 엄격히 준수합니다.

---

## 1. 개인정보 및 기기 데이터의 수집과 이용 목적

'앱'은 원칙적으로 사용자를 식별할 수 있는 개인정보를 외부 개발자 서버로 전송하거나 수집하지 않습니다. 런처 설정, 홈 화면 배치, 앱 단축키, 위젯 구성 등의 모든 데이터는 사용자의 기기 내부(Jetpack DataStore 및 앱 전용 저장 공간)에만 로컬로 저장됩니다.

단, 원활한 런처 기능 제공 및 인앱 결제, 광고 표시를 위해 다음의 데이터가 로컬에서 처리되거나 제3자(Google) 서비스와 연동될 수 있습니다.

1. **설치된 애플리케이션 정보 (`QUERY_ALL_PACKAGES`)**:
   - **목적**: 기본 홈 화면(런처) 앱으로서 기기에 설치된 앱 목록을 로드하여 홈 그리드 및 앱 서랍에 표시하고, 사용자가 앱을 실행/검색/배치할 수 있도록 지원하기 위해 필수적으로 사용됩니다.
   - **보관 및 전송 여부**: 오직 사용자 기기 메모리 및 로컬 저장소에서만 실시간으로 처리되며, 외부 서버로 절대 수집 또는 전송되지 않습니다.
2. **연락처 정보 (`READ_CONTACTS` - 선택 사항, Premium 전용)**:
   - **목적**: 사용자가 검색창에서 직접 연락처를 검색하고, 검색 결과에서 전화 앱의 발신 화면과 문자 앱의 작성 화면을 바로 열 수 있도록 지원합니다. 앱이 직접 전화를 걸거나 문자를 발송하지는 않습니다.
   - **보관 및 전송 여부**: 기기 로컬의 연락처 데이터베이스를 실시간으로 검색 필터링하는 데에만 사용되며, 연락처 목록을 별도로 저장하거나 외부 서버로 일체 전송하지 않습니다.
3. **인앱 결제 데이터 (Google Play Billing v7.x)**:
   - **목적**: Keyrium Premium 1회성 영구 구매 및 구매 복원(Restore Purchases) 처리를 위해 구글 플레이 결제 시스템과 통신합니다.
   - **보관 및 전송 여부**: 결제 토큰 및 구매 확인 데이터는 구글 플레이 서버에서 안전하게 관리되며, 기기 내부에는 라이선스 활성화 여부만 안전하게 캐싱됩니다.
4. **광고 관련 데이터 (Google AdMob)**:
   - **목적**: 무료(Free) 버전 사용자에게 배너 광고를 송출하기 위해 사용됩니다. Premium 구매 시 광고 및 관련 데이터 처리는 즉시 중단됩니다.
   - **수집 항목**: 광고 ID(ADID/GAID), 기기 모델, 대략적인 위치 정보, 앱 상호작용 지표 등이 구글에 의해 비식별 형태로 처리될 수 있습니다.
   - **동의 관리(EEA/UK)**: 유럽 경제 지역 및 영국 사용자에게는 앱 최초 실행 시 Google User Messaging Platform(UMP) 동의 폼이 표시되며, 사용자가 동의하기 전에는 광고가 로드되지 않습니다. 동의 내용은 앱 설정의 `[광고 개인정보 옵션]`에서 언제든 변경할 수 있습니다.
5. **알림 접근 (선택 사항, Premium 전용)**:
   - **목적**: 앱 아이콘·폴더에 읽지 않은 알림 개수 뱃지를 표시하고 상단바에 알림 인디케이터를 표시하기 위해, 사용자가 시스템 설정에서 직접 허용한 경우에만 활성 알림의 개수를 실시간 집계합니다.
   - **보관 및 전송 여부**: 알림 제목·본문 등 내용은 읽거나 저장하지 않고 발신 앱별 개수만 메모리에서 집계하며, 어떤 데이터도 외부로 전송하지 않습니다. 권한을 해제하면 즉시 중단됩니다.
6. **접근성 서비스 (선택 사항)**:
   - **목적**: 사용자가 접근성 설정에서 직접 허용한 경우, ① 홈 화면 빈 공간 두 번 탭으로 화면 끄기(생체 잠금 유지), ② 상단바에서 알림 패널 열기 두 가지 시스템 동작만 수행합니다.
   - **보관 및 전송 여부**: 화면 내용을 읽지 않으며 어떤 데이터도 수집·저장·전송하지 않습니다.
7. **사용자가 직접 고른 파일 및 진단 로그 (선택 사항)**:
   - **목적**: 사용자가 직접 고른 배경화면 이미지, 사용자 지정 글꼴·타건음·아이콘 파일과 홈 화면 백업 파일(`.json`)을 사용하고, 설정에서 진단 로그를 켠 경우 문제 분석용 로그를 앱 전용 저장 공간에 기록합니다.
   - **보관 및 전송 여부**: 모두 기기 안에만 저장되며 자동으로 전송되지 않습니다. 사용자가 설정의 `[개발자에게 로그 보내기]`를 눌러 이메일 등 공유 앱을 직접 선택해 보낸 경우에만 개발자에게 전달됩니다.
8. **음성 검색 및 외부 앱 연동 (선택 사항)**:
   - **목적**: 마이크 키는 기기에 설치된 음성 인식 앱을 호출하여 검색어를 받아옵니다. 검색창의 `g`·`y`·`naver` 명령은 입력한 검색어를 해당 검색 앱 또는 브라우저에 전달하고, `c`·`m`·`al`·`t` 명령은 전화·문자·시계 앱을 엽니다.
   - **보관 및 전송 여부**: Keyrium은 마이크 권한을 요청하지 않으며 음성을 녹음·저장하지 않습니다. 음성 처리와 검색은 사용자가 선택한 외부 앱이 해당 앱의 개인정보 처리방침에 따라 수행하며, 사용자가 명령을 실행했을 때에만 이루어집니다.

---

## 2. 앱 권한 (Permissions) 사용 안내

'앱'은 필수적이고 정당한 기능 수행을 위해서만 다음의 권한을 요청하고 사용합니다.

| 권한 (Permission) | 유형 | 사용 목적 |
| :--- | :--- | :--- |
| `QUERY_ALL_PACKAGES` | 필수 (매니페스트 선언) | 기본 홈 화면(런처)으로서 기기에 설치된 전체 앱 목록 조회, 표시 및 실행 |
| `READ_CONTACTS` | 선택 (런타임 권한, Premium 전용) | 통합 검색창에서 연락처 실시간 검색 및 빠른 전화/문자 발송 |
| 알림 접근 (`BIND_NOTIFICATION_LISTENER_SERVICE`) | 선택 (사용자가 시스템 설정에서 직접 활성화, Premium 전용) | 앱 아이콘·폴더의 읽지 않은 알림 개수 뱃지 및 상단바 알림 인디케이터 표시. 알림 내용을 읽거나 저장하지 않고 개수만 집계하며 외부로 전송하지 않습니다. |
| 접근성 서비스 (`BIND_ACCESSIBILITY_SERVICE`) | 선택 (사용자가 접근성 설정에서 직접 활성화) | ① 홈 화면 빈 공간 두 번 탭 시 화면 끄기(지문·얼굴 잠금 해제 유지), ② 상단바에서 알림 패널 열기. 화면 내용을 읽지 않으며(`canRetrieveWindowContent=false`) 어떤 데이터도 수집·전송하지 않습니다. |
| `INTERNET` | 필수 | 구글 플레이 인앱 결제 라이선스 검증 및 AdMob 광고 로드 |
| `ACCESS_NETWORK_STATE` | 필수 | 상단바 Wi-Fi/모바일 네트워크 연결 상태 아이콘 표시, 결제·광고 네트워크 가용성 확인 |
| `VIBRATE` | 필수 | 가상 쿼티 키보드 타건 햅틱, 트랙패드·드래그·더블탭 피드백 |
| `EXPAND_STATUS_BAR` | 필수 | 상단바 탭 시 시스템 알림 패널 열기 |
| `com.android.alarm.permission.SET_ALARM` | 필수 | 검색창 퀵 액션의 알람·타이머를 시스템 시계 앱에 등록 |
| `BIND_APPWIDGET` | 필수 (매니페스트 선언) | 홈 화면 위젯 바인딩 (기본 홈 앱 지정 시 시스템이 자동 승인) |
| `com.google.android.gms.permission.AD_ID` | 필수 (AdMob SDK) | AdMob 광고 ID (Free 버전 광고 전용, EEA/UK 는 UMP 동의 후에만 사용) |
| `ACCESS_ADSERVICES_AD_ID`, `ACCESS_ADSERVICES_ATTRIBUTION`, `ACCESS_ADSERVICES_TOPICS` | SDK 포함 (Google 광고 SDK) | Android 개인정보 보호 샌드박스 기반 광고 측정 (Free 버전 광고 전용) |
| `WAKE_LOCK`, `FOREGROUND_SERVICE` | SDK 포함 (Google 광고·백그라운드 작업 라이브러리) | 광고 SDK의 내부 작업 처리. 앱이 자체적으로 포그라운드 서비스를 실행하지는 않습니다. |
| `com.android.vending.BILLING` | 필수 | Google Play Billing 인앱 결제 연동 |

---

## 3. 개인정보의 보유 및 파기

모든 설정 및 런처 구성 데이터는 사용자 기기 내 로컬 샌드박스 영역에만 보관됩니다.
- 사용자가 앱을 기기에서 삭제(제거)하거나 '앱 데이터 삭제'를 실행하면, 모든 로컬 데이터는 즉시 영구 파기됩니다.
- 로컬 백업 파일(`.json`)을 생성한 경우, 해당 파일은 사용자가 지정한 저장 경로에만 존재하며 사용자가 직접 파일을 삭제하여 파기할 수 있습니다.
- 진단 로그 파일(파일당 최대 2MB, 최근 5개만 유지)은 앱 전용 저장 공간에 있으며, 설정에서 삭제하거나 앱 데이터를 삭제하면 함께 파기됩니다.

---

## 4. 제3자 서비스 제공 및 SDK 연동

'앱'은 안정적인 서비스 제공을 위해 신뢰할 수 있는 구글의 공식 SDK만을 포함하고 있습니다.

- **Google Play Services / Billing**: [https://policies.google.com/privacy](https://policies.google.com/privacy)
- **Google AdMob**: [https://support.google.com/admob/answer/6128543](https://support.google.com/admob/answer/6128543)

---

## 5. 문의 및 개인정보 보호책임자

개인정보 처리 및 보안과 관련한 문의사항이나 의견이 있으신 경우 아래 연락처로 문의해 주시기 바랍니다.

- **개발자 / 지원 이메일**: ietersacrum@gmail.com
- **개발자 웹사이트**: [https://bahnseo.github.io/](https://bahnseo.github.io/)

---

## 6. 개정 및 공지

본 개인정보 처리방침은 법령 개정 또는 서비스 기능 변경에 따라 수정될 수 있습니다.
- **공고일자**: 2026년 9월 7일
- **시행일자**: 2026년 9월 7일 (v1.1.0 정식 출시)
- **최종 수정일자**: 2026년 9월 19일 (실제 앱 동작과 권한 목록에 맞춰 내용 보완)

<br><br>

================================================================================

<br><br>

# Privacy Policy (English)

This Privacy Policy explains how 'Keyrium Launcher' (hereinafter referred to as 'the App') processes and protects your personal information and device data. We highly respect your privacy and strictly adhere to the Google Play Developer Program Policies.

---

## 1. Collection and Use of Personal Information & Device Data

In principle, the App does not collect or transmit any personally identifiable information to external developer servers. All launcher preferences, home screen layouts, shortcuts, and widget placements are stored locally on your device (using Jetpack DataStore and app-private storage).

The following data is processed locally or integrated with Google services to provide core launcher functionality:

1. **Installed Application Inventory (`QUERY_ALL_PACKAGES`)**:
   - **Purpose**: As a core home screen launcher (`CATEGORY_HOME`), accessing installed applications is indispensable for indexing, displaying, searching, and launching apps from the home screen grid and app drawer.
   - **Storage & Transmission**: Processed in real time only within the local device memory and storage. Never collected, stored, or transmitted to any external server.
2. **Contacts Information (`READ_CONTACTS` - Optional, Premium Only)**:
   - **Purpose**: Enables real-time contact search directly within the launcher search bar, and opens the phone app's dialer or the messaging app's compose screen from a result. The App itself does not place calls or send messages.
   - **Storage & Transmission**: Processed locally for query matching only upon explicit user runtime consent. Never transmitted to external servers or logged.
3. **In-App Purchase Data (Google Play Billing v7.x)**:
   - **Purpose**: Manages one-time lifetime Premium purchases and license restoration via Google Play Billing.
   - **Storage & Transmission**: All payment transactions are securely handled by Google Play. Only the local purchase state is cached securely on your device.
4. **Advertising Data (Google AdMob)**:
   - **Purpose**: Serves banner advertisements to Free version users. Purchasing Premium stops ad serving and related data processing immediately.
   - **Collected Items**: Advertising IDs (ADID/GAID), device specifications, coarse location, and ad performance metrics may be processed by Google in an anonymized form.
   - **Consent management (EEA/UK)**: Users in the European Economic Area and the UK are shown a Google User Messaging Platform (UMP) consent form on first launch; no ads are loaded until consent is given. Consent choices can be changed at any time from **Ad privacy options** in the app settings.
5. **Notification Access (Optional, Premium Only)**:
   - **Purpose**: Only when the user enables it in system settings, the App counts active notifications in real time to show an unread-count badge on app icons/folders and a notification indicator in the status bar.
   - **Storage & Transmission**: Notification titles, bodies, and other content are never read or stored — only per-app counts are tallied in memory. No data is transmitted anywhere. Revoking the permission stops this immediately.
6. **Accessibility Service (Optional)**:
   - **Purpose**: Only when the user enables it in Accessibility settings, the App performs two system actions: (1) turning the screen off on a home-screen double-tap (biometric unlock preserved), and (2) opening the notification shade from the status bar.
   - **Storage & Transmission**: Screen content is never read, and no data is collected, stored, or transmitted.
7. **User-Selected Files and Diagnostic Logs (Optional)**:
   - **Purpose**: Uses the wallpaper image, custom font / typing-sound / icon files and home-screen backup file (`.json`) that you choose yourself, and, if you turn diagnostic logging on in Settings, records logs for troubleshooting in app-private storage.
   - **Storage & Transmission**: All of it stays on your device and is never sent automatically. It reaches the developer only if you tap **Send Log to Developer** in Settings and choose an email or sharing app yourself.
8. **Voice Search and External App Integration (Optional)**:
   - **Purpose**: The microphone key launches a voice recognition app already installed on your device and receives the recognized text. The `g`, `y` and `naver` search commands pass the text you typed to the search app or browser, and the `c`, `m`, `al` and `t` commands open the phone, messaging and clock apps.
   - **Storage & Transmission**: The App does not request the microphone permission and does not record or store audio. Voice processing and searches are performed by the external app you choose under that app's own privacy policy, and only when you run a command.

---

## 2. App Permissions Usage

The App requests only necessary permissions strictly required to perform its stated features:

| Permission | Type | Usage Purpose |
| :--- | :--- | :--- |
| `QUERY_ALL_PACKAGES` | Essential (Manifest Declaration) | Core Home Launcher functionality: Discovering, indexing, and launching all installed applications |
| `READ_CONTACTS` | Optional (Runtime, Premium Only) | Just-in-time contact search in the search bar with instant Call/SMS actions |
| Notification access (`BIND_NOTIFICATION_LISTENER_SERVICE`) | Optional (enabled by the user in system settings, Premium Only) | Shows an unread-count badge on app icons/folders and a notification indicator in the status bar. Counts only — notification content is never read, stored, or transmitted. |
| Accessibility Service (`BIND_ACCESSIBILITY_SERVICE`) | Optional (enabled by the user in Accessibility Settings) | (1) Turn the screen off on a home-screen double-tap, keeping fingerprint/face unlock; (2) open the notification shade from the status bar. Screen content is never read (`canRetrieveWindowContent=false`) and no data is collected or transmitted. |
| `INTERNET` | Essential | Google Play Billing license verification and AdMob ad delivery |
| `ACCESS_NETWORK_STATE` | Essential | Wi-Fi / mobile network status icons in the status bar; billing and ad network availability checks |
| `VIBRATE` | Essential | Haptic feedback for the virtual QWERTY keyboard, trackpad, drag, and double-tap gestures |
| `EXPAND_STATUS_BAR` | Essential | Open the system notification shade when the status bar is tapped |
| `com.android.alarm.permission.SET_ALARM` | Essential | Register alarms/timers from search-bar quick actions in the system clock app |
| `BIND_APPWIDGET` | Essential (Manifest Declaration) | Bind home-screen widgets (auto-granted by the system when set as the default home app) |
| `com.google.android.gms.permission.AD_ID` | Essential (AdMob SDK) | AdMob advertising ID (Free-tier ads only; used only after UMP consent in the EEA/UK) |
| `ACCESS_ADSERVICES_AD_ID`, `ACCESS_ADSERVICES_ATTRIBUTION`, `ACCESS_ADSERVICES_TOPICS` | Included by SDK (Google ads SDK) | Ad measurement based on the Android Privacy Sandbox (Free-tier ads only) |
| `WAKE_LOCK`, `FOREGROUND_SERVICE` | Included by SDK (Google ads / background-work libraries) | Internal task handling of the ads SDK. The App does not run a foreground service of its own. |
| `com.android.vending.BILLING` | Essential | In-App Purchases for Keyrium Premium |

---

## 3. Data Retention and Deletion

All user preferences and launcher settings reside strictly within the app's local sandbox storage on your device.
- Uninstalling the App or clearing app data in Android Settings permanently and immediately erases all stored data.
- User-created backup files (`.json`) are stored solely at the storage location selected by the user and can be deleted directly at any time.
- Diagnostic log files (up to 2 MB each, only the latest 5 kept) live in app-private storage and are erased when you delete them in Settings or clear the app data.

---

## 4. Third-Party Services & SDKs

The App integrates only official, trusted SDKs provided by Google:

- **Google Play Services & Billing**: [https://policies.google.com/privacy](https://policies.google.com/privacy)
- **Google AdMob**: [https://support.google.com/admob/answer/6128543](https://support.google.com/admob/answer/6128543)

---

## 5. Contact Information

If you have any questions or concerns regarding this Privacy Policy, please contact:

- **Developer / Support Email**: ietersacrum@gmail.com
- **Website**: [https://bahnseo.github.io/](https://bahnseo.github.io/)

---

## 6. Policy Updates

This Privacy Policy is effective as of the official release date and may be updated in accordance with applicable laws or feature updates.
- **Published Date**: September 7, 2026
- **Effective Date**: September 7, 2026 (v1.1.0 Global Release)
- **Last Revised**: September 19, 2026 (updated to match the App's actual behavior and permission list)
