후딱가게 (Hooddak) 🍽️ -> 2025.10.30 신버전 배포완료 (ios & android)
"후딱가게를 이용해주셔서 감사합니다."

후딱가게는 사용자의 위치 기반으로 근처 맛집을 추천하고, 랜덤 추천 기능을 통해 새로운 맛집을 발견할 수 있는 Flutter 기반 모바일 애플리케이션입니다.

📱 주요 기능
🏠 홈 화면
위치 기반 가게 추천: 사용자 위치 2km 이내의 맛집 추천
랜덤 추천: 4km 이내 영업 중인 가게 중 랜덤 선택 (룰렛 애니메이션)
실시간 지도: 네이버 지도를 활용한 가게 위치 표시
가게 상태 표시: 영업 중/준비중 상태 실시간 확인
🔍 검색 및 탐색
카테고리별 검색: 카페, 술집, 식당 등 장르별 필터링
지도 상세보기: 가게 위치와 정보를 지도에서 확인
가게 상세 정보: 메뉴, 영업시간, 리뷰 등 상세 정보 제공
👤 사용자 인증
카카오 로그인: 카카오톡 앱 또는 카카오 계정 로그인
일반 로그인: 이메일/비밀번호 기반 로그인
회원가입: 단계별 회원가입 프로세스
아이디/비밀번호 찾기: 계정 복구 기능
❤️ 즐겨찾기
가게 즐겨찾기: 관심 가게 저장 및 관리
즐겨찾기 목록: 저장된 가게 목록 확인
🏪 사장님 기능
가게 등록 및 관리: 사장님용 가게 정보 등록/수정
메뉴 관리: 가게 메뉴 추가/수정/삭제
영업 상태 관리: 가게 영업/휴업 상태 변경
가게 정보 수정: 가게 소개, 연락처, 영업시간 등 관리
🛠 기술 스택
Frontend
Flutter: 3.2.0+ (최신 SDK)
Dart: 3.2.0+
상태 관리: Provider 패턴
UI: Material Design 3
주요 패키지
지도: flutter_naver_map - 네이버 지도 연동
인증: kakao_flutter_sdk - 카카오 로그인
위치: geolocator, geocoding - GPS 위치 서비스
상태 관리: provider - 상태 관리
네트워킹: http - API 통신
로컬 저장: shared_preferences - 로컬 데이터 저장
이미지: image_picker, image_cropper - 이미지 처리
애니메이션: lottie - 고품질 애니메이션
분석: firebase_analytics - 사용자 행동 분석
Backend 연동
API 서버: https://hooddak.com/api/
인증: JWT 토큰 기반 인증
데이터: JSON 형태의 RESTful API
📁 프로젝트 구조
hooddak_25.3/
├── hooddak/                    # 메인 Flutter 프로젝트
│   ├── lib/
│   │   ├── homepage/          # 홈 화면 관련
│   │   ├── searchpage/        # 검색 화면 관련
│   │   ├── ownerpage/         # 사장님 기능
│   │   ├── likepage/          # 즐겨찾기
│   │   ├── main_navigation/   # 메인 네비게이션
│   │   └── ...
│   ├── assets/               # 이미지, 폰트 등 리소스
│   └── pubspec.yaml          # 의존성 관리
└── hooddak_app/              # 추가 Flutter 프로젝트
    └── ...                   # 동일한 구조
🚀 설치 및 실행
사전 요구사항
Flutter SDK 3.2.0 이상
Dart SDK 3.2.0 이상
Android Studio / Xcode (개발용)
네이버 지도 API 키
카카오 개발자 계정
설치 방법
저장소 클론
git clone https://github.com/Lcmind/hooddak_25.3.git
cd hooddak_25.3/hooddak
의존성 설치
flutter pub get
API 키 설정

lib/main.dart에서 네이버 지도 클라이언트 ID 설정
lib/main.dart에서 카카오 네이티브 앱 키 설정
앱 실행

# Android
flutter run

# iOS
flutter run -d ios
🔧 최근 업데이트 (2025.10.30)
프로젝트 통합
✅ hooddak과 hooddak_app 두 프로젝트를 하나의 저장소로 통합
✅ 포괄적인 .gitignore 설정으로 불필요한 파일 제외
✅ GitHub 저장소에 모든 소스 코드 업로드 완료
기술 스택 업데이트
✅ Flutter SDK: 최신 버전으로 업데이트
✅ Dart SDK: 3.2.0+ 최신 버전
✅ 패키지 의존성: 모든 패키지를 최신 버전으로 업데이트
✅ Firebase: 최신 Firebase Core 및 Analytics 적용
코드 품질 개선
✅ 상태 관리: Provider 패턴으로 일관된 상태 관리
✅ 에러 처리: Firebase 초기화 실패 시 graceful fallback
✅ 성능 최적화: 불필요한 빌드 파일 제거
✅ 코드 정리: 중복 코드 제거 및 구조 개선
📱 지원 플랫폼
Android: API 21+ (Android 5.0+)
iOS: iOS 11.0+
macOS: macOS 10.14+
Windows: Windows 10+
Linux: Ubuntu 18.04+
🤝 기여하기
Fork the Project
Create your Feature Branch (git checkout -b feature/AmazingFeature)
Commit your Changes (git commit -m 'Add some AmazingFeature')
Push to the Branch (git push origin feature/AmazingFeature)
Open a Pull Request
📄 라이선스
이 프로젝트는 개인 프로젝트입니다. 상업적 사용을 원하시면 연락해주세요.

📞 문의
개발자: Lcmind
이메일: ckealss@naver.com
GitHub: https://github.com/Lcmind/hooddak_Readme
후딱가게와 함께 새로운 맛집을 발견해보세요! 🍽️✨
