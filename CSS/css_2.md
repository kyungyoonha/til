## 벤더 프리픽스란?

### 사용 이유?

-   caniuse.com 에서 transform 과 같은 속성을 검색하면 프리픽스를 붙여야 사용가능한 css를 확인할 수 있다.
-   크롬: -webkit-
-   파이어폭스: -moz-
-   IE: -ms-

```CSS
.className {
    -webkit-transform: translate(-100px, 100px);
       -moz-transform: translate(-100px, 100px);
        -ms-transform: translate(-100px, 100px);
         -o-transform: translate(-100px, 100px);
            transform: translate(-100px, 100px);
}
```

### 플러그인

-   autoPrefix css
-   자동으로 넣어줌
