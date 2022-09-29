# split_by_dots_commas_spaces
<!DOCTYPE html>
<html>
<body>

<?php
function words_array($str) {
  	$arr = [];
  	$z = array(".", ",");
	$onlyspace = str_replace($z, "", $str);
    $arr = explode(" ", $onlyspace);
	return $arr;
}
$str = "Buổi sáng, ông mặt trời thức dậy.";
$e = words_array($str);
echo "<pre>";
var_dump($e);



?>

</body>

https://www.w3schools.com/php/phptryit.asp?filename=tryphp_function1
https://stackoverflow.com/questions/7757751/how-do-you-change-a-repository-description-on-github
https://www.php.net/manual/en/function.explode.php
https://www.php.net/manual/en/function.str-replace.php
