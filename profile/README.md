# 📢 NotiSKKU - 성균관대학교 공지사항 알림 서비스

NotiSKKU는 성균관대학교 학생들을 위한 **맞춤형 공지사항 알림 애플리케이션**입니다.
학과별, 키워드별로 공지사항을 받아보고, 중요한 공지를 즐겨찾기하며, 학사일정을 한눈에 확인할 수 있습니다.

<br/>

## 🔥 This is Our Team

| PM | Design | Frontend | Backend |
|:--:|:------:|:--------:|:-------:|
| <img src="readme_assets/chaeyeon.png" width="150" alt="이채연" tabindex="-1" style="outline:none;border:0;"/> | <img src="readme_assets/jungyoon.jpeg" width="150" alt="박정윤" tabindex="-1" style="outline:none;border:0;"/> | <img src="readme_assets/songmok.jpeg" width="150" alt="이송목" tabindex="-1" style="outline:none;border:0;"/> | <img src="readme_assets/chaejoo.jpeg" width="150" alt="이채주" tabindex="-1" style="outline:none;border:0;"/> |
| 성균관대학교 4기 | 성균관대학교 4기 | 성균관대학교 4기 | 성균관대학교 4기 |
| 이채연 | 김예진 | 문준원 | 박준우 |
| [@i-chaeyeon](https://github.com/i-chaeyeon) | [@twjin03](https://github.com/twjin03) | [@mppn98](https://github.com/mppn98) | [@junwooP0](https://github.com/junwooP0) |

<br/>

## ✨ 주요 기능

### 1. 📋 공지사항 탭
- **학과별 공지 조회**: 최대 2개 학과 선택 및 전환 가능
- **카테고리 필터링**: 전체, 학사, 입학, 취업, 채용/모집, 장학, 행사/세미나, 일반
- **실시간 업데이트**: Firebase Firestore를 통한 최신 공지 제공
- **공지 유형**: 전체 공지, 단과대 공지, 학과별 공지

### 2. 🔍 키워드 탭
- **맞춤형 키워드 설정**: 관심 있는 키워드로 공지 필터링
- **사용자 정의 키워드**: 직접 키워드 추가 및 관리
- **개발자 제공 키워드**: 자주 사용되는 키워드 제공
- **푸시 알림 설정**: 키워드별 알림 수신 여부 설정

### 3. ⭐ 즐겨찾기 탭
- **공지 북마크**: 중요한 공지사항 저장
- **편집 모드**: 즐겨찾기 공지 일괄 관리
- **빠른 접근**: 저장한 공지사항 빠르게 확인

### 4. 📅 학사일정 탭
- **월간 캘린더**: 학사일정을 캘린더 형식으로 제공
- **일정 상세보기**: 날짜별 일정 확인 가능
- **드래그 시트**: 위로 드래그하여 오늘 일정 확인
- **멀티데이 이벤트**: 여러 날에 걸친 일정 표시

### 5. 🔔 더보기 탭
- **알림 설정**: 학과별, 키워드별 푸시 알림 관리
- **서비스 정보**: FAQ, 이용약관, 개인정보처리방침
- **피드백**: 서비스 개선 의견 제출


<br/>

## 🛠️ 기술 스택

### Frontend
- **Flutter** 3.7.0+
- **Dart** ^3.7.0

### State Management
- **Riverpod** (flutter_riverpod 2.6.1)     
- **Provider** 6.1.2

### Backend & Database
- **Firebase Core** 3.13.  
- **Firebase Firestore** 5.6.6
- **Firebase Cloud Messaging** 15.2.5 

<br/>

## 🚀 시작하기

<br/>

## 📱 지원 플랫폼
- ✅ Android
- ✅ iOS


<br/>



<br/>

## 🔐 개인정보 보호
- 사용자 데이터는 로컬 기기에 저장 (SharedPreferences)
- Firebase Cloud Messaging을 통한 푸시 알림만 서버 통신
- 공지사항 조회는 읽기 전용으로 개인정보 수집 없음

<br/>

## 📄 라이선스
이 프로젝트는 MIT 라이선스 하에 배포됩니다. 자세한 내용은 [LICENSE](License) 파일을 참조하세요.


<br/>

## 📞 문의 및 피드백
서비스 관련 문의사항이나 개선 제안은 다음을 통해 연락해주세요:
- GitHub Issues: [Issues 페이지](https://github.com/Team-Notiskku/NotiSKKU/issues)
- 앱 내 피드백 기능 이용

<br/>

## 🎉 기여하기
1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<br/>

---
Made with ❤️ by Team Notiskku
