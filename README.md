# 🏟️ Baseball Simulation Application

<div align="center">
  <img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" />
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" />
  <img src="https://img.shields.io/badge/Retrofit-009688?style=for-the-badge&logo=retrofit&logoColor=white" />
  <img src="https://img.shields.io/badge/Jetpack Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white" />
</div>

## 📋 프로젝트 소개
이 프로젝트는 야구 경기 시뮬레이션을 위한 Android 애플리케이션입니다. 실제 야구 경기의 상황을 시뮬레이션하고, 선수 교체에 따른 승률 변화를 예측하는 기능을 제공합니다. AI 기술을 활용하여 선수들의 성적과 경기 상황을 분석하여 더 정확한 시뮬레이션 결과를 제공합니다.

## ⚾ 주요 기능
### 📅 일별 야구 경기 일정 조회
- 2024 시즌 경기 일정 제공 (3월 23일 ~ 10월 1일)

### 🎮 실시간 경기 상황 시뮬레이션
- 이닝별 상황 분석
- 베이스 상황 표시
- 아웃 카운트 관리

### 📊 선수 교체 시 승률 예측
- 타자/투수 교체 시 승률 변화 예측
- 선수별 상세 스탯 비교

### 👥 팀별 라인업 정보 조회
- 선발 라인업
- 벤치 선수
- 불펜 투수

### 🎥 경기 하이라이트 정보 제공
- 주요 교체 상황 하이라이트
- 팀별 점수 표시

## 🛠️ 기술 스택
<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/kotlin/kotlin-original.svg" alt="kotlin" width="40" height="40"/>
        <br>Kotlin
      </td>
      <td align="center">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/android/android-original.svg" alt="android" width="40" height="40"/>
        <br>Android SDK
      </td>
    </tr>
  </table>
</div>

## 📱 시스템 요구사항
- Android SDK 33 이상
- Kotlin 1.9.0 이상
- Android Studio Hedgehog 이상

## 🔧 설치 방법
1. 프로젝트를 클론합니다:
```bash
git clone https://github.com/JongHyun070105/Baseball_Simulation_App.git
```

2. Android Studio에서 프로젝트를 엽니다.

3. 필요한 의존성을 설치합니다:
```bash
./gradlew build
```

4. 앱을 실행합니다.

## 📖 사용 방법
1. 메인 화면에서 원하는 날짜의 경기를 선택합니다.
2. 경기 하이라이트 화면에서 시뮬레이션을 시작할 수 있습니다.
3. 선수 교체가 필요한 상황에서 교체할 선수를 선택합니다.
4. 시뮬레이션 결과를 확인합니다.

## 📁 프로젝트 구조
```
app/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/example/baseball_simulation_app/
│   │   │       ├── API/           # API 관련 클래스
│   │   │       ├── data/          # 데이터 모델 및 리포지토리
│   │   │       ├── ui/            # UI 관련 클래스
│   │   │       └── utils/         # 유틸리티 클래스
│   │   └── res/                   # 리소스 파일
```

## 📄 라이센스
이 프로젝트는 MIT 라이센스를 따릅니다.
