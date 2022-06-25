# Calculator
Javascript Calculator Assignment

<!DOCTYPE html>
<html lang="en" dir="ltr">
    <html> 
        <head>
            <title>Calculator</title>
          </head> 
        <body>  
        <script>  
        const operator = prompt('Enter operator to perform the calculation ( either +, -, * or / ) in the box below: ');  
          
        // accepting the number from user  
        const number1 = parseFloat(prompt ('Enter the first number: '));  
        const number2 = parseFloat(prompt ('Enter the second number: '));  
          
        let result;   
          
        if (operator == '+') { 
            result = number1 + number2;  
        }  
        else if (operator == '-') { 
            result = number1 - number2;  
        }  
        else if (operator == '*') { 
            result = number1 * number2;  
        }  
        else {  
            result = number1 / number2; 
        }  
          
        // displaying the result of the Calculator  
        window.alert(" Result is " + result);  
        </script>  
        </body>  
        </html> 
