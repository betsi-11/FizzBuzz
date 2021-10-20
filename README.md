# FizzBuzz
Displaying 1-100 but instead of numbers that are multiples of 3 printing Fizz, multiple of 5 printing Buzz and multiples of both 3 &amp; 5 printing FizzBuzz using php and Javascript

php code

for ($i=1; $i<=100; $i++){

    if($i % 3==0 && $i % 5==0){
    
        echo "FizzBuzz <br>";
    }
    
    else if($i % 3==0){
        echo "Fizz <br>";
    }
    
    else if($i % 5==0){
        echo "Buzz <br>";
    }
            
    else {
        echo $i;
        echo "<br>";
    }

}

Javascript Code


for(let i=1; i <= 100; i++){

    if(i % 3==0 && i % 5==0){
        document.writeln("FizzBuzz <br/>");
        
    }
    else if(i % 3 ==0){
        document.writeln("Fizz <br/>");
    }
    else if(i % 5 ==0){
        document.writeln("Buzz <br/>");
    }
    
    else {
        document.writeln(i+"<br/>");
    }
}
