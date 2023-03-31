# HTML 소개

---

HTML은 Hypertext Markup Language의 약자이며, 웹페이지를 만드는 데 사용하는  마크업 언어이다.

웹페이지는 HTML태그로 구성되어있다.

## HTML 태그

---

HTML의 태그는 아래와 같이 구성되어있다.

```html
<태그이름> //여는 태그
내용
</태그이름> //닫는 태그
```

<!DOCTYPE html> : 웹 문서의 유형을 html로 지정

<html> : 모든 html 태그의 최상위 태그

<head> : 제목, 스크립트, 스타일 시트 와 같은 문서 정보를 담는다

<p> : 단락을 정의한다

<a> : 앵커 태그 href속성을 통해 다른 페이지 파일 위치를 다른 URL로 연결할 수 있는 하이퍼링크를 만든다

<h1>~<h6> : 제목을 나타낸다

~

## HTML 태그 속성

---

HTML 태그는 태그마다 속성을 부여할 수 있다.

태그의 속성은 **<태그 속성="값">** 형태로 사용하고태그마다 여러 속성을 부여 할 수도 있다.

```html
<a herf="https://github.com">GITHUB</a>
```

위와 같이 <a>태그의 **href**속성을 사용하여 하이퍼링크를 만들 수 있다. 

속성에는 id, class, style 등과 같은 여러 속성이 있다.

## HTML 기본 구조

---

```html
<!DOCTYPE html>
<html lang="ko">
  <head>
    <meta charset="utf-8">
    <title>문서의 제목을 입력해주세요</title>
  </head>
  <body>
    <!-- 웹 브라우저를 통해 보이는 내용을 입력해주세요 -->
  </body>
</html>
```

HTML문서의 기본 구조는 위와 같다

## HTML 예시

---

```html
<!DOCTYPE html>
<html lang="ko">
<head>
  <title>HTML 연습</title>
</head>
<body>
  <h1>HTML 소개</h1>
  <h2>HTML은 마크업 언어입니다.</h2>
  <img src="./이미지/html5로고.png" alt="html5 로고입니다." width="300">
</body>
</html>
```

![Untitled](HTML%20%E1%84%89%E1%85%A9%E1%84%80%E1%85%A2%20e38932056936460f9c68a8fe7ed31eba/Untitled.png)