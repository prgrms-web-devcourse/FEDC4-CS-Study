표준 폰트가 아닌 폰트 디자인 웹 폰트를 사용하거나 웹 서버에 폰트 파일(.eot,.woff등)을 올려두고 사용한다.

```jsx
@font-face {
	font-family: 'Roboto-Medium';
	src: local('Roboto-Medium'),
			 url(Roboto-Medium.woff2) format('woff2'),
       url(Roboto-Medium.woff) format('woff'),
			 url(Roboto-Medium.ttf) format('truetype'),
       url(Roboto-Medium.otf) format('opentype'),
	font-display: swap;
}
```
