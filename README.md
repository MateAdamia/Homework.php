# Homework.php

<?php

 $num1=0;
 $num2 = 0;
 $state = true;
 $mult=(int)$num1 * (int)$num2;
 do{

    echo "num1: \n";
    $num1=readline();
    echo"num2: \n";
    $num2 =readline();
    if($num1==0 or $num2==0){
        break;
    }
    elseif($num1>100){
        echo"number must be less then 100";
    }
    elseif($num2>100){
        echo"number must be less then 100";
        
    }
    
    else{
        $mult=(int)$num1 * (int)$num2;
        echo $mult;
        $state = false;
    }
    
    

     
 }while($state != false)
 
?>
