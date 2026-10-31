# 김상윤

**Frontend Developer**

측정 결과를 바탕으로 문제의 원인을 좁혀 가는 프론트엔드 개발자입니다.  
시도한 방법과 확인한 결과를 기록하고, 동료와 논의하며 끝까지 해결합니다.

<p>
  <a href="https://blog091.tistory.com/" title="개발 블로그 읽기"><img src="https://img.shields.io/badge/TECH%20BLOG-24292F?style=for-the-badge&amp;logo=tistory&amp;logoColor=FF5544" alt="개발 블로그" /></a>&nbsp;
  <a href="mailto:ksy151020@gmail.com" title="ksy151020@gmail.com으로 이메일 보내기"><img src="https://img.shields.io/badge/EMAIL-24292F?style=for-the-badge&amp;logo=gmail&amp;logoColor=EA4335" alt="이메일 보내기: ksy151020@gmail.com" /></a>
</p>

<br />

## Featured Project

### 주차의 민족

**목적지 주변 주차장을 탐색하고 추천받는 모바일 웹 서비스**  
<sub>2026.08 ~ · React · TypeScript · TanStack Query · Naver Maps SDK · Webpack</sub>

- **더 가벼운 첫 화면** · 7개 페이지를 분리하고 미사용 상세 라우트를 정리해 초기 main 번들을 **629 → 521 KiB, 약 17% 축소**했습니다.
- **측정에 근거한 지도 최적화** · 지도 이동을 자동화해 생성·Paint·프레임 비용을 나눠 측정하고, zIndex 변경으로 발생하던 **불필요한 마커 재생성 10회**를 속성 갱신으로 대체했습니다.
- **실제 응답까지 확인하는 타입 안전성** · **6개 API에 Zod 검증**을 적용하고 Sentry에서 확인한 응답·타입 불일치를 해결했습니다.

<details>
<summary>지도 최적화에서 배운 것</summary>

<br />

LOD와 조회 범위를 함께 바꾼 초기 기록에서는 dropped frame이 111 → 16으로 줄었습니다. 하지만 이를 LOD만의 효과로 단정하지 않았습니다. 변경 요인을 분리해 다시 측정했고, 작은 아이콘이 일관된 프레임 개선으로 이어진다는 결론은 내리지 않았습니다.

**좋아 보이는 결과보다, 설명할 수 있는 결과를 중요하게 생각합니다.**

[마커 렌더링 비용을 다시 측정한 과정 읽기](https://blog091.tistory.com/80)

</details>

<br />

## Experience

### 우아한테크코스 · Web Frontend 8기
<sub>2026.02 ~ 2026.11</sub>

[활동 아카이브](https://github.com/yuncic/woowacourse-archive) 
- 5번의 페어 프로그래밍과 현직자 코드 리뷰로 컴포넌트·훅의 책임과 추상화 범위를 다듬었습니다.
- 이미지·번들을 최적화하고 Lighthouse·LCP로 전후 결과를 확인했습니다.
- SDD로 진행한 MVP 개발 경험을 테코톡에서 발표했습니다.

### 크몽 · 데이터 수집 자동화 서비스 개발·운영
<sub>2022.06 ~ 2022.11 · Python · JavaScript · pandas · Selenium · BeautifulSoup</sub>

[서비스 주소](https://kmong.com/gig/368592)

- 인스타그램 팔로워·유튜브 등 **데이터 수집 자동화 4건을 유료 납품**했습니다.
- 고객과 요구사항·작업 범위를 직접 조율하고, 약속한 기한 내 결과물을 전달했습니다.

<br />

## Tech Stack

<p>
  <img src="https://img.shields.io/badge/React-202F45?style=flat-square&amp;logo=react&amp;logoColor=8BC8FF" alt="React" />
  <img src="https://img.shields.io/badge/TypeScript-202F45?style=flat-square&amp;logo=typescript&amp;logoColor=8BC8FF" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-202F45?style=flat-square&amp;logo=javascript&amp;logoColor=8BC8FF" alt="JavaScript" />
  <img src="https://img.shields.io/badge/TanStack_Query-202F45?style=flat-square&amp;logo=reactquery&amp;logoColor=8BC8FF" alt="TanStack Query" />
</p>

**Frontend** &nbsp; React · TypeScript · JavaScript · TanStack Query · Emotion  
**Quality & Tooling** &nbsp; Zod · Jest · Sentry · Webpack · pnpm  
**Automation** &nbsp; Python · pandas · Selenium · BeautifulSoup

<br />

## Problem Solving

<a href="https://solved.ac/ksy0725/"><img src="https://mazassumnida.wtf/api/v2/generate_badge?boj=ksy0725" alt="Solved.ac Profile · ksy0725" /></a>
