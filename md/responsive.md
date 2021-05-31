## grid layout
---
- viewport; 스마트폰 화면에서 실제 내용이 표시되는 영역. <head>태그에 작성.
- 웹사이트를 여러 개의 column으로 나누어 각 요소를 화면에 맞게 배치
- grid; 바둑판, 격자
- 화면을 규칙적 배열, 레이아웃 일관성, 안정감, 업데이트 용이, 요소를 자유롭게 배치
- 크롬 개발자 도구 - 디바이스 모드
- 미디어 쿼리; 디바이스에 따라 사이트의 형태가 바뀌도록 CSS를 작성하는 방법
  - 모바일 퍼스트 기법; 모바일용 css는 태블릿, 데스크톱에도 기본으로 적용되므로 모바일 레이아웃을 기본으로 CSS 완성. 이후 태블릿, 데스크톱에 맞춰 기능, 스타일 추가하는 방식.
- 플렉서블 박스 레이아웃
  - 수평or수직 중 한 쪽을 주축으로 박스를 배치.
  - display; 플렉스 컨테이너로 묶고 display로 지정해야 함.
  - flex-direction ; 주축과 방향 지정
  - flex-wrap; 줄 바꾸기
  - flex-flow; direction+wrap 한번에 지정. 배치 방향 결정, 줄 바꿈.
  - justify-content; 주축을 기준으로 정렬
  - aling-items; 교차축을 기준으로 정렬
  - aling-self; 특정 항목만 정렬 방법을 지정
  - aling-content; 여러 줄일때 간격 지정
  - 항상 중앙에 표시 ; {display:flex; justify-content:center; align-items:center; min-height:100vh;}

- CSS 그리드 레이아웃
  - 가로 줄row 세로 컬럼colulmn 모두 사용해서 배치. 2차원. 레고식.
  - 