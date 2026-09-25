---
title: Signal Room 개인정보 처리방침
---

# Signal Room 개인정보 처리방침

시행일: 2026년 9월 25일

Signal Room(이하 "앱")은 "제로원바이브코딩" 만든 보이스 음질 분석 앱입니다. 이 방침은 앱이 어떤 정보를 다루는지, 그리고 어떤 정보를 다루지 않는지를 설명합니다.

## 요약

- 앱은 **개인정보를 수집하거나 서버로 전송하지 않습니다.**
- 마이크 소리는 **기기 안에서만 실시간으로 분석**되고, 녹음 파일로 저장되거나 외부로 보내지지 않습니다.
- 회원가입, 로그인, 광고, 분석 도구(애널리틱스), 추적 기능이 없습니다.

## 1. 마이크 사용

앱은 사용자가 "실시간 분석 시작"을 누른 경우에만 마이크를 사용합니다.

- 입력된 소리는 주파수 대역, 레벨, 음량 등을 계산하는 데만 쓰입니다.
- 소리는 기기의 메모리에서 잠깐 처리된 뒤 바로 버려집니다. 녹음 파일로 저장하지 않습니다.
- 소리와 분석 결과는 개발자나 제3자에게 전송되지 않습니다.
- 분석을 멈추거나 앱이 백그라운드로 가면 마이크 사용이 중지됩니다.

마이크 권한은 기기의 **설정 > Signal Room**에서 언제든 끌 수 있습니다.

## 2. 로컬 네트워크 사용 (선택 기능)

사용자가 직접 X32/M32 믹서의 IP 주소를 입력하고 연결한 경우에만, 앱은 같은 Wi-Fi 안의 해당 믹서와 OSC(UDP 10023) 방식으로 통신합니다.

- 통신 대상은 사용자가 입력한 사설 IP 주소(예: 192.168.x.x)의 믹서뿐입니다.
- 주고받는 내용은 EQ, HPF, 컴프레서 등 채널 설정값입니다.
- 인터넷의 다른 서버와는 통신하지 않습니다.

로컬 네트워크 권한은 **설정 > Signal Room**에서 끌 수 있습니다.

## 3. 기기에 저장되는 정보

앱은 사용 편의를 위해 다음 정보를 **사용자의 기기 안에만** 저장합니다.

- 스피치/노래 모드별 채널 EQ·컴프 설정값
- 조정 안내를 적용한 기록(시간, 항목, 값)

이 정보는 기기 밖으로 전송되지 않으며, 앱을 삭제하면 함께 삭제됩니다.

## 4. 보고서 내보내기 (선택 기능)

사용자가 "세션 보고서 내보내기"를 누르면, 측정값과 설정값을 담은 JSON 파일이 만들어지고 iOS 공유 화면이 열립니다. 파일을 어디로 보낼지는 사용자가 직접 선택하며, 앱이 자동으로 전송하지 않습니다.

## 5. 제3자 제공 및 추적

앱은 어떤 정보도 제3자에게 제공하거나 판매하지 않습니다. 광고 식별자(IDFA)를 사용하지 않으며, 다른 회사의 앱이나 웹사이트에 걸친 추적을 하지 않습니다.

## 6. 아동의 개인정보

앱은 개인정보를 수집하지 않으므로 아동의 개인정보도 수집하지 않습니다.

## 7. 방침의 변경

이 방침이 바뀌면 이 페이지에 새 내용과 시행일을 게시합니다.

## 8. 문의

개인정보와 관련한 문의는 아래로 연락해 주세요.

- 개발자: 제로원 바이브코딩
- 이메일: luminwis@gmail.com

---

# Signal Room Privacy Policy (English)

Effective date: September 25, 2026

Signal Room ("the app") is a voice tone analysis app made by zeroonevibecoding.

- **No personal data is collected or sent to any server.**
- Microphone audio is analyzed **on the device only, in real time**. It is not recorded, stored or transmitted.
- There is no account, login, advertising, analytics or tracking.

**Microphone.** Used only after you tap "실시간 분석 시작" (Start live analysis), to measure frequency bands and levels. Audio is processed in memory and discarded immediately. You can turn microphone access off in Settings > Signal Room.

**Local network (optional).** Only when you enter the IP address of an X32/M32 mixer, the app exchanges channel settings (EQ, HPF, compressor) with that mixer on your local Wi-Fi over OSC (UDP 10023). It does not contact any internet server.

**On-device storage.** Channel settings per mode and a history of applied suggestions are stored only on your device and are deleted when you delete the app.

**Report export (optional).** When you choose to export a session report, a JSON file is created and the iOS share sheet opens; you decide where it goes.

**Third parties and tracking.** No data is shared with or sold to third parties. The app does not use the advertising identifier and does not track you across apps or websites.

**Children.** The app does not collect personal data from anyone, including children.

**Changes.** Updates to this policy will be posted on this page with a new effective date.

**Contact.** zeroonevibecoding · [contact email]
