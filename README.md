# android-with-expo 📱

> 안드로이드 개발에 발을 담그기 위해 [Expo](https://expo.dev) + React Native + TypeScript 조합으로 시작한 학습 repo. 처음부터 네이티브 빌드를 잡지 않고, **Expo의 file-based routing**으로 빠르게 화면 단위 학습에 집중했습니다.

## 🎯 학습 목표

- Expo 프로젝트 구조와 file-based routing(`app/`)에 익숙해지기
- React Native 컴포넌트로 화면 만들기
- 안드로이드 에뮬레이터 / 실기기에 띄워보기 (네트워크 IP 자동 추출 스크립트 포함)

## 🗂 구조 (요약)

```
android-with-expo/
├── app/                # file-based routing (각 파일이 화면이 됨)
├── components/         # 재사용 컴포넌트
├── hooks/              # 커스텀 훅
├── constants/
├── assets/
├── scripts/
├── get_network_local_ip.js   # 실기기 디버깅용 로컬 IP 추출
├── app.json
└── package.json
```

## 🛠 기술 스택

- **Expo SDK** + **React Native**
- **TypeScript**
- **Expo Router** (file-based routing)

## 🚀 실행

```bash
npm install
npx expo start
```

- Android 에뮬레이터 / iOS 시뮬레이터 / Expo Go(QR 스캔) 중 선택해 띄울 수 있습니다.

## 💭 처음 모바일을 만져보며

- **웹과 다른 점**: 스크롤·터치·키보드 처리 등 웹에서는 브라우저가 알아서 해주던 것을 직접 다뤄야 한다는 걸 체감했습니다.
- **Expo의 장점**: 네이티브 환경 셋업의 진입장벽을 크게 낮춰줘서, 학습 단계에서는 화면/네비게이션 같은 본질에 집중할 수 있었습니다.
- **앞으로 더 해볼 것**: 상태 관리 라이브러리, 푸시 알림, 디바이스 API(카메라, 위치) 연동.
