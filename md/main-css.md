```css
body{
	background-color: #282828;
	margin: 0;
	height: 100vh;
}

.grid{
	display: grid;
	background-color: #928374;
	grid-template-columns: repeat(4, 1fr);
	grid-template-rows: 1fr 3fr 5fr 1.5fr; 
	grid-gap: 1rem 1rem;
	grid-template-areas:
		"n n n n"
		"h h h h"
		"m m m m"
		"f f f f";
	margin: 1rem;
	height: 100%;
}

nav, header, main, footer{
	border-style: solid;
	border-color: #f2e5bc;
	border-width: 2px;
}

nav{
	grid-area: n;
	background-color: #b8bb26;
}
header{
	grid-area: h;
	background-color: #7c6f64;
}
main{
	grid-area: m;
	background-color: #689d6a;
}
footer{
	grid-area: f;
	background-color: #fabd2f;
}

.nbtn{
	float: right;
}
```
