---
layout: about
title: about
permalink: /
subtitle: <a href="https://www.inu.ac.kr">인천대학교</a> 전자공학부 <b>지능형 시스템 및 데이터 과학 연구실</b>

profile:
  align: right
  image: logo.JPG        # <--- .jpg 대신 대문자 .JPG로 수정 (아인슈타인 사진 제거)
  image_circular: false
  address: >
    <p>인천광역시 연수구 아카데미로 119</p>
    <p>인천대학교 공과대학(8호관)</p>

selected_papers: false    # <--- true에서 false로 변경 (아래쪽 selected publications 제거)
social: true

announcements:
  enabled: false          # <--- true에서 false로 변경 (아래쪽 news 제거)
  scrollable: true
  limit: 5

latest_posts:
  enabled: false
---

인천대학교 **MINDS (Machine Intelligence and Data Science)** 연구실 홈페이지에 오신 것을 환영합니다. 6G(AI-RAN), AI 안전, 반도체 공정데이터 분야를 심도 있게 연구하고 있습니다.

<strong>[연구원 모집]</strong> 2026년 한국연구재단 개인기초연구(5년 과제) 선정에 따라 <b>석·박사 및 학부 연구생</b>을 모집합니다. AI, 반도체, 6G 등에 관심 있는 학생의 지원 바랍니다.(문의: <a href="mailto:hoon@inu.ac.kr">hoon@inu.ac.kr</a>)

### 주요 연구 분야 (Research Interests)

* 6G 및 차세대 통신
    * **Cell-free 네트워크:** 차세대 이동통신의 핵심인 분산형 네트워크 구조 및 최적화 연구
    * **AI-Native RAN:** 인공지능 기반 무선 접속망 리소스 관리 및 지능형 통신 기술 개발

* AI 윤리 및 표준화
    * **IEEE P7000/P8000:** 글로벌 AI 윤리 사양 표준화 참여 및 기술적 프레임워크 구축
    * **안전성 검증:** 신뢰할 수 있는 AI(Trustworthy AI)를 위한 보안 및 알고리즘 평가 체계 연구

* 반도체 공정 및 패키징 불량 분석
    * **반도체 AOI:** 딥러닝 기반의 반도체 패키징 자동 광학 검사 및 시리얼 번호 인식 고도화
    * **Mirror-Fab:** 가상 제조 플랫폼 데이터 분석을 통한 지능형 공정 효율화 시스템 구현

---

### 뉴스 및 공지사항

* **[2026-04-06] 김훈 교수, IEEE CertifAIEd 수석심사원 Master 과정 이수** : AI 윤리 인증 최고 과정인 마스터 클래스를 이수하여, 향후 국내외 AI 윤리 표준화 및 인증 심사 분야에서 선도적인 역할을 수행할 예정입니다.

* **[2026-04-06] 김훈 교수, 대한전자공학회(IEIE) 부회장 선임** : 대한전자공학회 부회장 및 기술정책위원장으로 선임되어, 국내 기술 정책 수립과 산학협력 활성화에 기추적인 역할을 수행하게 되었습니다.

* **[2026-03-20] IEEE Access 논문 게재 (제조 지능화 연구)** : 금속 표면 각인 번호 자동 인식을 위한 딥러닝 기술 연구가 IEEE Access에 게재되었습니다.

* **[2026-03-15] 한국연구재단 개인기초연구사업 선정** : 6G 및 AI 신뢰성 연구를 위한 5년 장기 국책 과제에 선정되었습니다. 해당 분야를 함께 개척해 나갈 열정 있는 학생 연구원을 상시 모집합니다.

<style>
  /* 1. 프로필 영역 전체를 우측 끝으로 바짝 붙이기 */
  .profile {
    float: right !important;
    position: relative !important;
    margin-left: 100px !important;  /* 본문 텍스트와의 왼쪽 간격 확보 */
    margin-right: 0px !important;   /* 우측 여백 제거하여 끝으로 붙임 */
    margin-top: 10px !important;
    width: 200px !important;       /* 프로필 영역의 전체 너비 고정 */
    z-index: 10;
  }

  /* 2. 로고 이미지 정렬 및 크기 */
  .profile img {
    width: 100% !important;        /* 위에서 정한 200px에 맞춤 */
    height: auto !important;
    display: block !important;
    margin-left: auto !important;  /* 이미지 자체도 우측 정렬 */
    box-shadow: none !important;   /* 그림자 제거하여 깔끔하게 배치 */
    border: none !important;
  }

  /* 3. 하단 자동 섹션(news 등) 차단 유지 */
  .news, #news, .publications, #selected-publications, .post-list-description {
    display: none !important;
  }

  /* 4. 모바일 화면에서도 로고가 겹치지 않게 처리 */
  @media (max-width: 800px) {
    .profile {
      float: none !important;
      display: block !important;
      margin: 0 auto 20px auto !important; /* 모바일에서는 중앙 정렬 */
      width: 150px !important;
    }
  }
</style>
