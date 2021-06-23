
![jeanD'arc](./img/wall-pre-jeandarc.jpg)



<details>
<summary> HTML </summary>

+ 3 part html
<details>
<summary> index </summary> 

```html
<!DOCTYPE html>
<html>
	<head>
		<meta name="viewport" content="width=device-width, initial-scale=1.0">
		<title>My PUBG ACADEMIA</title>
		<link rel="stylesheet" href="./css/main.css"/>
		<link rel="stylesheet" href="./css/mob-only.css"/>
	</head>
<style>
</style>

		<body>

			<div class="grid">
				<nav>
					<a class="nbtn" href="./contacts.html">Contact Us </a>
					<a class="nbtn" href="./about.html">About |</a> 
					<a class="nbtn" href="./index.html">Home | </a> 
				</nav>

				<header>
					header Home
				</header>

				<main>
					main
				</main>

				<footer>
					footer
				</footer>
			</div>

		</body>
</html>
```

</details>
<details>
<summary> about </summary>

```html
<!DOCTYPE html>
<html>
	<head>
		<meta name="viewport" content="width=device-width, initial-scale=1.0">
		<title>About</title>
		<link rel="stylesheet" href="./css/main.css"/>
		<link rel="stylesheet" href="./css/mob-only.css"/>
	</head>
<style>
header{
	background-color: #b16286;
}
</style>

		<body>

			<div class="grid">
				<nav>
					<a class="nbtn" href="./contacts.html">Contact Us </a>
					<a class="nbtn" href="./about.html">About |</a> 
					<a class="nbtn" href="./index.html">Home | </a> 
				</nav>

				<header>
					header about
				</header>

				<main>
					main
				</main>

				<footer>
					footer
				</footer>
			</div>

		</body>
</html>
```

</details>
<details>
<summary> contacts </summary>

```html
<!DOCTYPE html>
<html>
	<head>
		<meta name="viewport" content="width=device-width, initial-scale=1.0">
		<title>Contact us</title>
		<link rel="stylesheet" href="./css/main.css"/>
		<link rel="stylesheet" href="./css/mob-only.css"/>
	</head>
<style>
header{
	background-color: #076678;
}
</style>

		<body>

			<div class="grid">
				<nav>
					<a class="nbtn" href="./contacts.html">Contact Us </a>
					<a class="nbtn" href="./about.html">About |</a> 
					<a class="nbtn" href="./index.html">Home | </a> 
				</nav>

				<header>
					header contact us
				</header>

				<main>
					main
				</main>

				<footer>
					footer
				</footer>
			</div>

		</body>
</html>
```

</details>
</details>

<details>
<summary> CSS </summary>

+ 2 part CSS
<details>
<summary> main </summary>

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

</details>

<details>
<summary> mob-only </summary>

```css
/*---------FOR MOBILE-------------*/

/*--------(orientation: portrait)--------*/

@media only screen and (orientation: portrait)
and (max-width: 550px)
{
	.grid{
		margin: 0;
		grid-gap: 0;
		grid-template-columns: 1fr;
		grid-template-rows: .5fr 3fr 5.5fr 1fr;
	}
}


/*--------(orientation: landscape)--------*/

@media only screen and (orientation: landscape)
and (max-width: 900px)
{
	.grid{
		margin: 0;
		grid-gap: 0;
		grid-template-columns: 1fr;
		grid-template-rows: 10vh 35vh 50.5vh 20.2vh;
	}
}
```

</details>
</details>


