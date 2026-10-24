# 다락(DaRak) 개인정보처리방침

시행일: 2026년 10월 25일

다락은 사용자의 Windows PC에 설치해 쓰는 업무 관리 프로그램입니다. 다락을 만든 사람은 사용자의 자료를 받거나 보관하는 서버를 운영하지 않습니다.

## 1. 다락이 다루는 정보
- 사용자가 다락에 직접 입력한 일정·할 일·일지·메모·사람과 단체 정보 등은 **사용자의 PC에만** 저장됩니다.
- 사용자가 켠 동기화 기능에 따라, 같은 사용자의 다른 PC로 보내기 위해 **암호화된 묶음 파일**이 아래 서비스에 올라갈 수 있습니다.

## 2. 구글 드라이브 동기화(사용자가 켰을 때만)
- 다락은 구글 계정 권한 중 `drive.appdata`(다락 전용 숨김 폴더) **하나만** 요청합니다.
- 이 폴더에는 다락이 만든 **암호화된 동기화 파일**만 저장합니다. 암호를 푸는 열쇠는 사용자의 PC에만 있어 구글과 다락 제작자는 내용을 읽을 수 없습니다.
- 다락은 사용자 드라이브의 다른 파일·메일·연락처·프로필 정보를 읽거나 쓰지 않습니다.
- 구글 로그인 정보(갱신 토큰)는 사용자의 PC에 Windows 보호 저장소(DPAPI)로 암호화해 둡니다. 외부로 보내지 않습니다.
- 사용자는 다락 설정에서 언제든 연결을 끊을 수 있고(토큰 취소), 드라이브의 다락 동기화 파일을 지울 수 있습니다. 구글 계정 설정의 '타사 액세스'에서도 권한을 없앨 수 있습니다.

## 3. 제3자 제공
다락 제작자는 사용자의 정보를 수집하지 않으므로 제3자에게 제공하지 않습니다. 구글 API에서 받은 정보는 Google API 서비스 사용자 데이터 정책(제한적 사용 요건 포함)을 따르며, 동기화 외의 목적으로 쓰지 않습니다.

## 4. 문의
https://github.com/hsgamsa00-netizen/DaRak-releases/issues

---

# DaRak Privacy Policy (summary)

DaRak is a desktop app. Your data stays on your own PCs. If you turn on Google Drive sync, DaRak requests only the `drive.appdata` scope and stores only end-to-end encrypted sync files in its hidden app folder; neither Google nor the developer can read them. DaRak does not access any other Drive files, mail, contacts or profile data, and does not collect or share user data. Use of information received from Google APIs adheres to the Google API Services User Data Policy, including the Limited Use requirements. You can disconnect at any time in DaRak settings or in your Google Account's third-party access page.
