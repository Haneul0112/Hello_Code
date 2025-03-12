# 1주차 - Flutter 개발 환경 구성 및 Hello World 실행

## 1. Android Studio에 Flutter 플러그인 설치  
Flutter 개발을 위해 Android Studio에서 플러그인을 설치했습니다.  

### 설치 과정  
1. **Android Studio 실행**  
2. **메뉴에서** `File` → `Settings` (`Preferences` on macOS) 이동  
3. **좌측 메뉴에서 "Plugins" 선택 후 "Marketplace" 탭 클릭**  
4. **검색창에 `Flutter` 입력 후 설치**  
   - Dart 플러그인이 필요하다는 메시지가 나와서 함께 설치  
5. **설치 완료 후 Android Studio 재시작**  

✅ **헷갈렸던 점**  
처음에 Flutter 플러그인을 설치했는데 Dart 플러그인이 없어서 오류가 발생함.  
Dart 플러그인도 같이 설치해야 한다는 점을 깨달음!

---

## 2. Flutter SDK 다운로드 및 환경 변수 설정  
Flutter SDK를 다운로드한 후, 시스템에 인식되도록 설정했습니다.  

###  설치 과정  
1. [Flutter 공식 사이트](https://flutter.dev/docs/get-started/install)에서 SDK 다운로드  
2. 압축을 풀고 `C:\flutter` (Windows)경로에 저장  
3. 환경 변수에 `flutter/bin` 경로 추가  
   - **Windows**: `C:\flutter\bin`을 시스템 `Path` 변수에 추가    

✅ **헷갈렸던 점**  
환경 변수 설정을 했는데 `flutter doctor` 명령어가 실행되지 않음  
재부팅 후 다시 시도하니 정상적으로 실행됨!

---

## 3. Flutter Doctor 실행 및 프로젝트 생성  
### 📌 진행 과정  
1. 터미널(명령 프롬프트)에서 `flutter doctor` 실행  
   - Android Studio, Flutter, Dart 등이 정상적으로 인식되는지 확인  
2. 새로운 Flutter 프로젝트 생성  
