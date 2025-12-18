# 🚀 Park Jun Hyeon | Frontend Developer Portfolio

사용자 경험(UX)과 위트 있는 인터랙션을 지향하는 신입 프론트엔드 개발자 **박준현**의 포트폴리오입니다. 레트로한 윈도우 스타일과 카드 레이아웃을 컨셉으로 제작되었습니다.

## 🔗 Live Demo
[https://parkjunhyeon1209.github.io/Resume/](https://parkjunhyeon1209.github.io/Resume/)

## 🛠 Tech Stacks
- **Markup & Styling**: HTML5, CSS3
- **Responsive Design**: Media Queries, CSS Grid & Flexbox
- **Animation**: CSS Keyframes & Transitions

## ✨ Key Features
- **Retro UI Concept**: 90년대 윈도우 창과 비비드한 컬러 카드를 활용한 유니크한 디자인.
- **Interactive Elements**: 
  - 스킬 게이지 바 및 다양한 호버 이벤트.
  - 마우스 호버 시 멈추는 '찌리리공' 캐릭터 애니메이션 (`animation-play-state`).
- **YouTube Clone Section**: 실제 유튜브 모바일/PC UI를 참고하여 반응형 리스트 구현.
- **Responsive Layout**: PC(2열/교차 배치)에서 모바일(1열 배치)까지 완벽 대응.

## 💻 Technical Challenges & Solutions
### 1. 반응형 레이아웃 오차 해결
- **문제**: 카드들이 좌우로 삐져나온 디자인 특성상 1열 배치 시 여백이 틀어지는 문제 발생.
- **해결**: `%` 단위와 `calc()` 함수를 조합하고, 소수점 단위까지 세밀하게 위치를 조정하여 1px의 오차 없는 반응형 디자인을 구현하려 노력.

### 2. CSS 애니메이션 충돌 제어
- **문제**: 요소에 회전(Rotate)과 이동(Translate)을 동시에 적용 시 속성이 덮어씌워지는 현상.
- **해결**: 각 Keyframe 단계마다 모든 Transform 속성값을 명시하여 바뀌던 이미지의 높이를 조절함.

## ✍️ 소감 및 향후 계획
이번 프로젝트를 통해 이론으로만 알던 CSS의 깊은 동작 원리를 이해할 수 있었습니다. <br>
특히 반응형 디자인에서 Grid와 Flex를 언제 구분해서 써야 효율적인지 체감했습니다. <br>
앞으로 JavaScript를 활용하여 더 역동적인 데이터 바인딩과 스크롤 이벤트를 구현해 볼 계획입니다.

---
© 2025 Park Jun Hyeon.
