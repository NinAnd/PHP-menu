# PHP-menu
3. semester, Modul 2, opgave 1.

<!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>Ninettes PHP-menu</title>
</head>

<body>
	
	<?php 
	// $curpage = current page/den side vi befinder os på 
	// basename ($_SERVER['PHP_SELF']) viser filnavnet for den sti vi er på, fx index.php
		$curpage = basename ($_SERVER['PHP_SELF']);
	?>
	<!-- Liste over hvad hjemmesiden/menuen indholder, klargjort med links til hver enkelt underside -->
	<ul>
        <li><a href="index.php"<?php if ($curpage == 'index.php') {echo 'class="active"';}?>>Home</a></li>
        <li><a href="work.php"<?php if ($curpage == 'work.php') {echo 'class="active"';}?>>Work</a></li>
        <li><a href="about.php"<?php if ($curpage == 'about.php') {echo 'class="active"';}?>>About</a></li>
        <li><a href="contact.php"<?php if ($curpage == 'contact.php') {echo 'class="active"';}?>>Contact</a></li>
    </ul>

</body>
</html>
