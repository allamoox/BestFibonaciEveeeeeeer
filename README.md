# BestFibonaciEveeeeeeer
The Best Fibonaci You will ever see
<?php 

function fib($max){
    $a=0;
    $b=1;
    $result=array();
    
    for ($i=0 ; $i < $max ;$i++){
        $result[]=$a;
        $temp=$a+$b;
        $a=$b;
        $b=$temp;
    }
return($result);
}

print_r(fib(11));
?>
