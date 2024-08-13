# Intel One Mono

[배포처 바로가기](https://github.com/intel/intel-one-mono)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Intel One Mono`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/IntelOneMono/IntelOneMono.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/IntelOneMono/IntelOneMono.css');
```

### CSS `@font-face`

```css
/* normal */
@font-face {
    font-family: 'Intel One Mono';
    font-weight: 300;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/IntelOneMono/IntelOneMono-Light.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IntelOneMono/IntelOneMono-Light.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IntelOneMono/IntelOneMono-Light.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IntelOneMono/IntelOneMono-Light.ttf') format('truetype');
}
@font-face {
    font-family: 'Intel One Mono';
    font-weight: 400;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/IntelOneMono/IntelOneMono-Regular.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IntelOneMono/IntelOneMono-Regular.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IntelOneMono/IntelOneMono-Regular.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IntelOneMono/IntelOneMono-Regular.ttf') format('truetype');
}
@font-face {
    font-family: 'Intel One Mono';
    font-weight: 500;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/IntelOneMono/IntelOneMono-Medium.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IntelOneMono/IntelOneMono-Medium.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IntelOneMono/IntelOneMono-Medium.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IntelOneMono/IntelOneMono-Medium.ttf') format('truetype');
}
@font-face {
    font-family: 'Intel One Mono';
    font-weight: 700;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/IntelOneMono/IntelOneMono-Bold.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IntelOneMono/IntelOneMono-Bold.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IntelOneMono/IntelOneMono-Bold.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IntelOneMono/IntelOneMono-Bold.ttf') format('truetype');
}

/* italic */
@font-face {
    font-family: 'Intel One Mono';
    font-weight: 300;
    font-style: italic;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/IntelOneMono/IntelOneMonoItalic-Light.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IntelOneMono/IntelOneMonoItalic-Light.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IntelOneMono/IntelOneMonoItalic-Light.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IntelOneMono/IntelOneMonoItalic-Light.ttf') format('truetype');
}
@font-face {
    font-family: 'Intel One Mono';
    font-weight: 400;
    font-style: italic;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/IntelOneMono/IntelOneMonoItalic-Regular.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IntelOneMono/IntelOneMonoItalic-Regular.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IntelOneMono/IntelOneMonoItalic-Regular.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IntelOneMono/IntelOneMonoItalic-Regular.ttf') format('truetype');
}
@font-face {
    font-family: 'Intel One Mono';
    font-weight: 500;
    font-style: italic;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/IntelOneMono/IntelOneMonoItalic-Medium.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IntelOneMono/IntelOneMonoItalic-Medium.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IntelOneMono/IntelOneMonoItalic-Medium.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IntelOneMono/IntelOneMonoItalic-Medium.ttf') format('truetype');
}
@font-face {
    font-family: 'Intel One Mono';
    font-weight: 700;
    font-style: italic;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/IntelOneMono/IntelOneMonoItalic-Bold.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IntelOneMono/IntelOneMonoItalic-Bold.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IntelOneMono/IntelOneMonoItalic-Bold.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IntelOneMono/IntelOneMonoItalic-Bold.ttf') format('truetype');
}
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.


```css
font-family: "Intel One Mono", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
라이센스 본문
Copyright (c) 2023 Intel Corp. with Reserved Font Name "Intel One Mono", "IntelOne Mono" 
 
This Font Software is licensed under the SIL Open Font License, Version 1.1. 
 
This license is copied below, and is also available with a FAQ at: http://scripts.sil.org/OFL 
 
----------------------------------------------------------- 
SIL OPEN FONT LICENSE Version 1.1 - 26 February 2007 
----------------------------------------------------------- 
 
라이선스 전문 보기
```
