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
