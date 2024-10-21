# 영도체

[배포처 바로가기](http://ydct.or.kr/artcity/about/)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Yeongdo`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/Yeongdo/Yeongdo.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/Yeongdo/Yeongdo.css');
```

### CSS `@font-face`

```css
@font-face {
  font-family: 'Yeongdo';
  font-weight: normal;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/Yeongdo/Yeongdo.woff2') format('woff2'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/Yeongdo/Yeongdo.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/Yeongdo/Yeongdo.otf') format('opentype'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/Yeongdo/Yeongdo.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/Yeongdo/subsets/Yeongdo-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url("https://cdn.jsdelivr.net/gh/fonts-archive/Yeongdo/subsets/Yeongdo-dynamic-subset.css");
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.

```css
font-family: "Yeongdo", -apple-system, BlinkMacSystemFont, "Segoe UI",Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
영도체 글꼴 저작권 안내 
 
폰트명(한글/영문) : 영도체/Yeongdo 
 
저작권자 : 영도구청, 영도문화도시센터 
 
제작사 : 산돌, 산돌티움 
 
출시 년도 : 2021 
 
홈페이지(저작권자) 링크 : 
www.yeongdo.go.kr 
www.ydct.or.kr
 
영도체 글꼴은 개인 및 기업 사용자를 포함한 모든 사용자에게 무료로 제공되며 글꼴 자체를 유료로 판매하는 것을 제외한 상업적인 사용이 가능합니다. 
 
영도체의 글꼴 라이선스 전문을 포함하기 어려울 경우 출처 표기를 권장합니다. 
예) 이 페이지에는 영도문화도시센터에서 제공한 영도체 글꼴이 적용되어 있습니다. 
 
영도체 글꼴을 사용한 인쇄물, 광고물(온라인 포함)의 이미지는 영도체 프로모션을 위해 활용될 수 있습니다. 
 
영도체는 오픈 라이센스 글꼴로 동일한 저작권 규정을 적용받습니다.
```
