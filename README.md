fizzbuzz
========

var aux = true;

for( var i = 1 ; i<=100 ; ++i)
{
    
    if ( ( (i % 3) == 0) && ( (i % 5) == 0 ) )
    {
        alert("FizzBuzz");
        aux = false;
    }
    else
    {
       if( (i % 3) == 0)
       {
        alert("Fizz");
        aux = false;
       }        
       else
       {
           if((i % 5)== 0)
           {
               alert("Buzz");
               aux = false; 
           }
       }
    }
    if(aux == true)
    {
        alert(i);
    }
    
}
