## 시작

CSS Preprocessor.  
SCSS 로 작성한 코드는 컴파일 후 브라우저가 읽을 수 있는 CSS 로 변환됨.
gulp 를 사용하여 컴파일 가능.
gulp ..? 일단은 단순 복붙하여 사용.

```sh
$ npm i
$ npm run dev
```

html 이 바라보는 스타일 파일은 css 임.

## 변수

언더바로 시작하는 scss 파일 생성 및 import. $로 변수 만듦.

```sh
_variable.scss
$bg_color: pink;
```

## nesting

중괄호 안에 중괄호로 스타일 적용할 수 있음

```sh
.main {
  h1 {
    color: $subtitle;
  }
  button {
    &:hover {
      color: $subtitle;
    }
    color: $btn;
  }
}
```
