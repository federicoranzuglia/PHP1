# PHP1
<?php
/*
*calcolo della media dei voti
*/
$voti = array(5 , 6 , 8 , 4 , 7 , 6 , 9 , 5 , 6);
$limite=count($voti);
$somma = 0;
for($i=0; $i<$limite; $i++ )
{
	$somma += $voti[$i];
}
$media = $somma / $limite;
echo "<h2> Media dei voti: ". $media . "</h2>";
