---
title: Signal Room 개인정보 처리방침
---

# Signal Room 개인정보 처리방침

시행일: 2026년 9월 25일 (광고 추가 반영)

Signal Room(이하 "앱")은 "제로원 바이브코딩"에서 만든 보이스 음질 분석 앱입니다. 이 방침은 앱이 어떤 정보를 다루는지, 그리고 어떤 정보를 다루지 않는지를 설명합니다.

## 요약

- 개발자는 **개인정보를 수집하거나 서버로 전송하지 않습니다.**
- 마이크 소리는 **기기 안에서만 실시간으로 분석**되고, 녹음 파일로 저장되거나 외부로 보내지지 않습니다.
- 앱에는 Google AdMob **비맞춤형 광고**가 표시됩니다. 광고를 위해 Google이 일부 기기 정보를 처리합니다(5항).
- 회원가입, 로그인, 추적(ATT) 기능이 없습니다.

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

## 5. 광고 (Google AdMob)

앱은 화면 아래에 배너 광고를 표시하고, 분석을 마친 뒤 가끔(여러 번 사용할 때 한 번 정도) 전면 광고를 표시합니다. 사용자가 원할 때 보상형 광고를 보고 24시간 동안 광고를 끌 수 있습니다. 광고는 Google LLC의 AdMob을 통해 제공됩니다.

- **비맞춤형 광고만** 요청합니다. 사용자의 관심사에 맞춘 광고를 하지 않습니다.
- 광고 식별자(IDFA)를 요청하지 않으며, 추적 허용(ATT) 창을 띄우지 않습니다.
- 광고를 표시하고 부정 클릭을 막기 위해 Google은 기기 정보(앱 단위 기기 식별자, 기기 종류, OS 버전), IP 주소로 추정한 대략적 위치, 광고 노출·클릭 정보, 오류·성능 정보를 처리할 수 있습니다.
- 마이크 소리와 분석 결과는 광고에 사용되거나 Google에 전달되지 않습니다.
- Google이 정보를 처리하는 방식: [Google 개인정보처리방침](https://policies.google.com/privacy), [Google이 파트너의 앱에서 정보를 사용하는 방식](https://policies.google.com/technologies/partner-sites)
- 유럽 경제 지역(EEA)·영국 등 동의가 필요한 지역에서는 Google의 동의 화면이 표시될 수 있습니다.

## 6. 제3자 제공

위 5항의 광고 제공을 제외하면, 앱은 어떤 정보도 제3자에게 제공하거나 판매하지 않습니다.

## 7. 아동의 개인정보

개발자는 아동을 포함한 누구의 개인정보도 수집하지 않습니다. 광고는 모든 연령에 적합한 등급(G)으로만 요청합니다.

## 8. 방침의 변경

이 방침이 바뀌면 이 페이지에 새 내용과 시행일을 게시합니다.

## 9. 문의

개인정보와 관련한 문의는 아래로 연락해 주세요.

- 개발자: 제로원 바이브코딩
- 이메일: luminwis@gmail.com

---

# Signal Room Privacy Policy (English)

Effective date: September 25, 2026

Signal Room ("the app") is a voice tone analysis app made by zeroonevibecoding.

- **The developer does not collect personal data or send it to any server.**
- Microphone audio is analyzed **on the device only, in real time**. It is not recorded, stored or transmitted.
- The app shows **non-personalized** Google AdMob ads (see Advertising).
- There is no account, login or tracking (ATT).

**Microphone.** Used only after you tap "실시간 분석 시작" (Start live analysis), to measure frequency bands and levels. Audio is processed in memory and discarded immediately. You can turn microphone access off in Settings > Signal Room.

**Local network (optional).** Only when you enter the IP address of an X32/M32 mixer, the app exchanges channel settings (EQ, HPF, compressor) with that mixer on your local Wi-Fi over OSC (UDP 10023). It does not contact any internet server.

**On-device storage.** Channel settings per mode and a history of applied suggestions are stored only on your device and are deleted when you delete the app.

**Report export (optional).** When you choose to export a session report, a JSON file is created and the iOS share sheet opens; you decide where it goes.

**Advertising.** A banner ad is shown at the bottom, an occasional full-screen ad may appear after you stop an analysis, and you may choose to watch a rewarded ad to turn ads off for 24 hours. Ads are provided by Google AdMob and are requested as non-personalized ads only. The app does not request the advertising identifier (IDFA) or show a tracking prompt. To serve ads and prevent fraud, Google may process device information (an app-scoped device identifier, device model, OS version), approximate location derived from the IP address, ad impression and click data, and crash/performance data. Microphone audio and analysis results are never used for ads or sent to Google. See the [Google Privacy Policy](https://policies.google.com/privacy) and [how Google uses information from sites or apps that use its services](https://policies.google.com/technologies/partner-sites).

**Third parties.** Apart from ad serving by Google as described above, no data is shared with or sold to third parties.

**Children.** The developer does not collect personal data from anyone, including children. Ads are requested with a general-audience (G) content rating.

**Changes.** Updates to this policy will be posted on this page with a new effective date.

**Contact.** zeroonevibecoding · luminwis@gmail.com
