<?php
$limite = 1000000;
$cnt = (int)@file_get_contents('cnt.txt');
file_put_contents('cnt.txt', ++$cnt);
if ($cnt % $limite == 0) {
    echo '<img height="1" width="1" style="display:none" src="https://www.facebook.com/tr?id=123456789012345&ev=PageView&noscript=1">';
}
header('Location: https://www.mi-malist.com/doc_TVRNNmJnK2hrN09oWUJpUk9MblQ4Zz09');
?>
