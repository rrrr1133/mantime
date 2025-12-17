# 일만시간의 법칙 홈페이지 제작
HTML5 시멘틱 태그, CSS변수, 반응형 등 웹 표준과 유지보수성을 고려해서 제작한 일만시간의 법칙 홈페이지입니다.

## 1. 시멘틱 마크업
HTML5의 시멘틱 태그를 사용하여 구조적으로 마크업을 구현했습니다.
```HTML
<div class="main">
        <header>
            <img src="imges/title.png" alt="1만시간의 법칙">
            <p class="header-text">"연습은 어제의 당신보다 당신을 더 낫게 만든다."</p>
        </header>
        <section>
            <img src="./imges/“.png" alt="">
            <p><strong>1만 시간의 법칙</strong>은<br/>
            어떤 분야의 전문가가 되기 위해서는<br/>
            최소한 1만 시간의 훈련이 필요하다는 법칙이다.</p>
            <img src="./imges/”.png" alt="">
        </section>
```

## 2. CSS 변수(:root)를 통한 컬러시스템 구성
컬러 재사용 및 유지보수의 용이성을 고려해 CSS변수(:root)를 활용했습니다.
```CSS
:root{
    --main-color:#5B2386;
    --sub-color:#FCEE21;
    --text-color:#fff;
    --placeholder-color:#BABCBE;
}
```

## 3. CSS 클래스 네이밍 : 케밥 케이스(kebab-case) 적용
