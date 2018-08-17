## CSS 박스모델

HTML 태그는 사각형 박스로 다루어지며 각 HTML 태그 요소를 하나의 박스로 다룬다.

- 콘텐츠 : HTML 태그의 텍스트나 이미지가 출력되는 부분
- 패딩(padding) : 콘텐츠를 직접 둘러싸고 있는 내부 여백
- 테두리(border) : 패딩 외부의 테두리로서, 직선이나 점선 혹은 이미지로 테두리를 그릴 수 있음
- 여백(margin) : 박스의 맨 바깥 영역이며 테두리 바깥의 공간으로 인접한 아래위 이웃 태그의 박스와의 거리



## CSS 배치

- display : inline vs block
- **position** : static, relative, absolute, fixed
- **float** : left, right

### 상대배치 => position:relative

normal flow의 '기본 위치'에서 lefr, top, botoom, right 프로퍼티의 값만큼 이동한 **상대위치**에 배치

### 절대배치 => position:absolute

부모 태그 안에서의 상대좌표로 left, right, top, bottom을 정의하여 특정 위치에 배치하기

- 브라우저 크기가 변해도 절대 배치된 태그 위치는 변하지 않음

