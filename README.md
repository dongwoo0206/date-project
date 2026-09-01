# 🚨 Project: No-Escape Date Proposal

사용자의 선택권을 제한하여 원하는 결과('데이트 승낙')를 도출해내는 강력한 UI/UX 실험 프로젝트입니다.

## 💡 기획 의도
"거절이라는 옵션은 애초에 존재하지 않는다."
사용자가 부정적인 선택지('싫어')를 고르려고 할 때, DOM 이벤트를 탈취하여 선택 버튼의 좌표를 무작위로 변경시킴으로써 긍정적인 선택('응 좋아')을 강제합니다.

## ⚙️ Core Logic
- `mouseover` 이벤트 리스너를 통한 커서 감지
- `window.innerWidth` 및 `innerHeight`를 활용한 동적 화면 범위 계산
- `Math.random()`을 이용한 실시간 절대 좌표(`position: absolute`) 난수 생성 및 적용

## 💻 Tech Stack
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

## 🔗 Demo
👉 (https://dongwoo0206.github.io/date-project/)
