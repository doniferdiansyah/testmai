# testmai
Project untuk keperluaan tes masuk MAI


  
<?php 

    $str = 'level';
    $strLen = strlen($str)-1;
    $revStr = '';
    for($i=$strLen; $i>=0; $i--){
        $revStr.=$str[$i];
    }
    if($revStr == $str)
        echo 'Palindrome';
    else
        echo "Not Palindrome";

?>
