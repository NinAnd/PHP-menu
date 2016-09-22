# PHP-menu
3. semester, Modul 2, opgave 1.

@charset "utf-8";
/* CSS Document */

/*** Generelle styles ***/

body {
	background-color: #f0f2f2;
}

header {
	background-color: #7fcec9;
	margin: 0;
}

h1 {
	font-family: Gotham, "Helvetica Neue", Helvetica, Arial, sans-serif;
	text-align: center;
	font-size: 48px;
	color: #f0f2f2;
	padding: 30px;
	margin: 0;
}

h2 {
	font-family: Gotham, "Helvetica Neue", Helvetica, Arial, sans-serif;
	text-align: center;
	font-size: 40px;
	color: #7fcec9;
}

p {
	font-family: Georgia, serif;
	font-size: 20px;
	color: #626366;
	margin: 0 40px 20px 40px;
}

/*** Menu Styles ***/

#php-menu ul {
	text-align: center;
	background-color: #7fcec9;
	margin-top: 0;
	border-top: 2px solid #f0f2f2;
}

#php-menu li {
	font-family: Gotham, "Helvetica Neue", Helvetica, Arial, sans-serif;
	display: inline-block;
	margin-right: 50px;
	padding: 10px;
	font-size: 20px;
}

#php-menu li a {
	text-decoration: none;
	color: #f0f2f2;
}

/* Tekstændringer der viser hvilken underside man befinder sig på */
#php-menu .active {
	color: #626366;
	font-weight: 700;
	text-decoration: underline;
}

/* Teksten skifter farve når man holder musemarkøren over den */
#php-menu li:hover a {
	color: #626366;
}
