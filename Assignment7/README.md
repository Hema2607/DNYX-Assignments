# JavaScript Fundamentals Assignment

1. What is JavaScript?
   
     JavaScript is a Front-end language that is ussed make the website or webpage more dynamic. HTML and CSS can only structure and style the webpage, but it can add more dynamic features that can make the website attractive and interactive.
   
     JS plays a vital role in web development that is used to create dynamic and interactive websites and also it is uesd to implement complex actions.


2. Variables and types:


        let userAge = 35;
   
        var userName = "John";
   
        console.log("Name: "+ name + " ,Age: " + age);  //output: Name: John , Age: 35


3. Comments in JS:

        /* in the above i have created a person's age with let keyword. This keyword will allow the user or us to change the value. In the second line I have created another variable that will store the person's name. And at the last, I have displayed the output in the console window.*/

4. Operations:


        let num1 = 20;
   
        let nums2 = 5;
   
        let add = num1 + num2;
   
        let sub = num1 - num2;
   
        let multiply = num1 * num2;
   
        let divide = num1 / num2;

        console.log("Addition: " + add);  //output: 25
   
        console.log("Subtraction: " + sub);  //output: 15
   
        console.log("Multilpication: " + multiply);  //output: 100
   
        console.log("Division: " + divide);  //output: 4

5. Data Types:


      i.String:

         let name = "John";

      ii. Numbers:
   
         let a = 25; //integer

         let b = 34.6; //floating point

      iii. Boolean:

         let istrue = true;

         let isfalse = false;

      iv. Array:

         let arr = ["Javascript","HTML","CSS","Tailwind"];

6. Functions in JS:


         function greetUser(name){

               return `Hi, ${name}!`;

         }

         console.log(greetUser("John"));

7. If-Else in JS:
   

         let temperature = 25;
   
         if(temperature>30){
   
               console.log("It's hot now");
   
         }else{
   
               console.log("The temperature is moderate");
   
         }

      OUTPUT:

         The temperature is moderate
   
8. For loop:


         for(let i=1;i<=5;i++){

               console.log(i);
         }

   OUTPUT:

         1
         2
         3
         4
         5

         

9. Loose vs Strict Equality:


      => Loose equality is used to check whether two items are same irrespective of their data types.

         console.log(10=='10'); //output: true

      => Strict equality is used to check whether two items are same by considering their data types.

         console.log(10==='10') //output: false
    
     
      
      
