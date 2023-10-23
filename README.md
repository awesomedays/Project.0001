# Project.0001
- 절대강좌! 유니티 - 이재현

## Memo
- 저장소 재생성 -- .gitignore / .gitattributes 파일 역할 및 개념
- 현재 진도까지 다시 한번 따라가면서 복습 및 정리

## Note
- IDE 변경 -- Visual Studio Code ▶ Visual Studio 2022

# 01. 유니티 엔진의 소개

### 리얼타임 3D 플랫폼

### 유니티의 장점

- 멀티 플랫폼 지원
- 통합 개발환경
- 유니티 라이선스 정책
- 정보 공유를 위한 커뮤니티 활성화
- 에셋 스토어

### 유니티로 만들어진 게임 및 콘텐츠

### 유니티 설치

- 유니티 허브에서 로그인 또는 계정 생성
- 라이선스 활성화
- 유니티 에디터 설치

### 유니티 에디터 소개

- 유니티 에디터 구조
- 뷰
  - 프로젝트 뷰
  - 씬 뷰
  - 하이러키 뷰
  - 인스펙터 뷰
  - 게임 뷰
  - 콘솔 뷰
- 툴 바의 기능
  - 툴 버튼
  - 피봇 / 센터
  - 로컬 / 글로벌
  - Play / Pause / Step
  - 검색
  - 콜라보레이트
  - 서비스
  - 계정
  - 레이어
  - 레이아웃
- 단축키 설정

### 정리

# 02. 게임 개발 준비

### 이 책에서 개발할 게임 소개 및 개발 순서

### 프로젝트 생성

### 유니티 에디터의 환경설정
- 레이아웃
- 프로젝트 뷰의 칼럼

### 프로젝트 뷰의 체계적인 관리

### 캐릭터 모델 임포트하기
- 유니티 패키지를 통한 리소스 설치

### 애셋 스토어
- 무료 리소스 내려받기
  - Yughues Free Metal Materials
  - Skybox Volume 2
  - Barrel

### 정리

# 03. 게임 스테이지 제작

### 바닥 생성 및 배치

- [ ] 정보 -- 게임오브젝트의 Transform Position X, Y, Z 원점 설정
- [ ] 정보 -- 균등 스케일 vs 비균등 스케일

### 텍스처

- 텍스처의 해상도 조절

### 머터리얼

- 머터리얼의 자동 적용
- 머터리얼 생성
- Albedo, Normal Map 적용
  - [ ] 팁 -- 텍스처 슬롯에 연결된 텍스처 확대 기능
- 머터리얼 적용 방법
  - [ ] 팁 -- Mesh Filters, Mesh Renderer 컴포넌트
- 타일링 속성
- 프리뷰의 다양한 기능

### 셰이더 및 물리 기반 셰이딩

- 렌더링 모드
  - Opaque (기본값)
  - Cutout
  - Transparent
  - Fade
- 알베도
- 메탈릭 속성
- 노멀 맵
- 하이트 맵
- 오클루전
- 이미션
- 디테일 마스크
- [ ] 정보 -- Standard 셰이더 세부 정보 https://docs.unity3d.com/kr/current/Manual/shader-StandardShader.html\

### 프리팹

- 네스티드 프리팹
- 벽 만들기
- 프리팹 생성
  - [ ] 팁 -- 프리팹의 색상
- 프리팹의 복제 및 네이밍
- 스내핑 기능

### 조명

- Directional Light
  - [ ] 팁 -- Directional Light의 위치
- Point Light
- Spot Light
- Area Light

### 실시간 라이트매핑 기능

- Lighting Settings 에셋
- Auto Generate 옵션

### 하늘 표현 방식

- 6방면 스카이박스
- 스카이박스 적용
- 프로시저럴 스카이박스
  - Sun
  - Sun Size
  - Sun Size Convergence
  - Atmosphere Thickness
  - Sky Tint
  - Ground
  - Exposure
- 큐브맵 스카이박스
  - 6 Frame Layout(Cube Environment)
  - Latitude-Longitude(Cylinderical)
  - Mirrored Ball(Spheremap)
  - [ ] 팁 -- 큐브맵 정보 http://docs.unity3d.com/Manual/class-Cubemap.html
  - [ ] 정보 -- 6방면 스카이박스의 드로우콜 소모량

### 정리

# 04. 주인공 캐릭터 제작
