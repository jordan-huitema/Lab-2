# Lab-Two
Jordan Huitema

--Journal Week 3--

The main thing we focused on this week was repeatedly typeing console.log();. In between this we also focused on JavaScript Operators, we learned what they are and how to use them.

What have we learned?

Types of operators

Arithmetic Operator
>This group of operators preforms baisc mathmatical functions, the operators are
>   +  Addition             (1 + 1 = 2)
>   -  Subtraction          (2 - 1 = 1)
>   *  Multiplication       (5 x 5 = 25)
>   /  Division             (8 ÷ 2 = 4)
>   %  Remainder            (10 % 3 = 1)
>   ** To the power         (5^2 = 25)

Assignment Operator
>This group of operators sets, increments, decrements variables.
>   =   Assigns or sets the var                     (var = 1)
>   +=  Adds, then assigns the variable             (1 += 1) = 2
>   -=  Subtracts, then assigns the variable        (2 -= 1) = 1
>   *=  Multiplies, then assigns the variable        (5 * 2) = 10
>   /=  Divided, then assigns the variable          (10 /= 5) = 2
>   %=  Calculate remainder, then assign variable   (10 %= 3) = 1

Increment and Decrement Operator
>These operators are used to increase or decrease a var or value by 1, they can also be used to change the var or value before or after it is called
>   ++x Increments by 1 and then uses the variable
>   x++ Uses the variable and then increments by 1
>   --x Increments by 1 and then uses the variable
>   x-- Uses the variable and then increments by 1

Comparison Operator
>These operators are used to compare diffrent variables and values, they output true or false statements but can also output number values (1 or 0)
>   ==  Are the values equal
>   === Is the first value the same data type as the second AND the same value
>   !=  Are the values unequal
>   !== Is the first value the same data type as the second AND a diffrent value
>   <   Is the first value smaller than the second
>   >   Is the first value greater than the second
>   >=  is the first value greater or equal to the second
>   <=  is the first value smaller or equal to the second

Logical Operator
>Logical Operators are basic logic gates, OR AND NOT operators that are used everywhere
>   OR ||   If either input has a value || (or) will print true, this works the same with number values but will returns the first input with value
>       console.log(false || true);   One of the inputs have a value so the result is true
>       console.log(false || false);  None of the inputs have value so the result to false
>       console.log(55 || 1);   returns first input with value (55)
>       console.log(1 || 55);   returns first input with value (1)
>
>   AND &&  If both inputs have value then output true or the last value, else output false or no value
>       console.log(true && false);   //only one input is true so output flase
>       console.log(false && false);  //both inputs are false so output false
>       console.log(55 && 1);   //returns last value (1)
>       console.log(1 && 55);   //returns last value (55)
>
>   NOT !   If the input is 0 or empty output true, else output false
Strings
>   "var"   setting a variable or number value as a string can be useful if you want to print a series of sepreate number values one after the other without calculating the sum. number strings can be converted back to number values by useing any addition operator except the + one, this is because you cannot subtract or divide a text string so the program is forced to convert it to a value. Strings with character in them can be compared with the comparison operators, to do this JavaScript converts each character to a number value based on the character and case and then compares them.
>       eg 
>       ("a" == "a") = True
>       ("A" == "a") = False
>       ("a" > "b")  = False
>       ("a" < "b")  = True

What challenges did I encounter?

>This week the main thing I struggled with was not being able to type console.log(); quite fast enough, thankfully I overcame this obstical by using copy paste.

>The second thing I found a challenge was trying to recall what the js code was for ^ (to the power of) thankfully some quick googling solved this.

>The third and final thing I stumbled over this week was trying to explain what the %= operator acutally did and the proccess it used to get there, I managed to overcome this obstical by changing the x and y values at either end of the operator until I had a good idea what it was doing. I often find learning by trial and error easier to understand and a more permanent solution than simply being told the answer.