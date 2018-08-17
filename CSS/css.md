## CSS

> Cascading Style Sheet

HTML 문서의 색이나 모양 등 외관을 꾸미는 언어

#### CSS3의 기능

1. 색상과 배경
2. 텍스트
3. 폰트
4. 박스 모델(Box Model)
5. 비주얼 포맷 및 효과
6. 리스트
7. 테이블
8. 사용자 인터페이스(UI)


#### HTML문서에 CSS3 스타일 시트 만들기

- `<style></style>`태그에 스타일 시트 작성
- style 속성에 스타일 시트 작성
- 스타일 시트를 별도의 파일로 작성
  * `<link>` 태그나 `@import`로 불러 사용
     * `<link>`
     
     ```{html}
     <head>
         <link href="css.css" ype"text/css" rel="stylesheet">
     </head>
     ```
     * `@import`
     
     ```{html}
     <style>
         @import url(css.css);
     </style>