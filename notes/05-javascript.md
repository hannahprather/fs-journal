# JavaScript
<script> should be located at the bottom of the body but on the inside!!
        ex <script src="app.js></script>
two kinds of data typer
 - primative (value type)
      ex. number, string, bool
 - non primative (reference type)
      ex. object, array, function


vocab
string interpolation
dom (document object model)


primative 
let number = 5
let string = 'hello'
let bool = true

non primative 
let object = {thing: "its a thing"}
let arrray [1, 2, 3, 4, 5]
function example (){
  consol.log(i'm a function')
}

consol.log('sum', sum)


invoking = () 

operators
Number++  adds 1 every time
number--   subtracts 1 every time 
number +=  re assigns the calue of number 
number += 5 is the same as number = number + 5
number -= 5
number *= 5
number %= 2
let sum = 2 + number++ 

comparitice operators
number ==5 (returns a true or false value)
number ===5 (strictly equal)(checks for equality and data type)
number > 4
number < 6 
number >= 4
number <= 6
let sum = 2 + number

if you add string math to number math, it turs both into a string and will put one number in front of the other, not add them together.


objects are collections of data the are made up of a key and a value pair

string = "" '' ``
      `` are the only ones that can do interprolation 


bool operators (booleans only return true or false values) 
bool == bool (are these equal)
bool != bool (are these not equal)

double && will allow you to add another conditional 
        it will only return true if both sides are true

 doublw pikes || means or, replace the && for the || and if only one side is true then you will get true 

 how to flip a bool value (flipping a bool)
 assuming bool is true
 if(bool){
   bool = false
 } else {
   bool = true
 }  
 consol.log('post-flip', bool)

the shorter way to do that is (ternary)
 
bool == bool ? false : true
consol.log('post-flip',bool)

null means nothing, it means the comouter knows there is nothing



functions cowSays(){
  <!-- console.log('moo')               this is the definition of the function -->
 let animalElm = document.getElementById('animal')
 let saysElm = document.getElementById('moo')

document.getElementById('animal')
<!-- consol.log('animal elm",animalElm); -->
animalElm.innerText =' Cow'
saysElm.innerText =' moo'
}

cow()                                   this is envoking the function


function duckSays(){
  document.getElementById('animal').innerText = 'Duck'
  document.getElementById('says').interText = 'Quack'
  document.GetelementById('iamge').interHTML = ' <img class="img-fluid" src="duck.jpg" alt="" srcset="">
}

let dictionary = {

}

<button class="btn btn-dark w-100 my-2" onclick="cowSays()">cow says</button>



Feb 9, 2022

LOOK INTO TRUTHY ANd FALSEY
(when you write a line of code test it right awaay so you can fix it)

1. make the layout in html for your ice cream shop
      once we get to java script we will comment a lot of it out

2. finish all your designs in css 

3. makes first function in js drawMenue
          line 38-41

4. build out menue array lines 3 - 24

5. whrites new function MAKES TEMPLATE (draw menue)
lines 26-31  


6. gives every object on the array an id

7. assign the dom from the drawMenue function from step 4

8. makes buyCoffee function 
lines 56-63

9. writes another function draw cart()) to get the cart to show up on our page
lines 48-50

10. add the dom to function drawCart

11. in the draw cart dom put the let  at the top total= 0
in the for each 
total += item.praice right over the template

12. add antoehr dom on drawCart 
document.getElementById('total').innertext = total.toFixed(2)     on line 66

13. add checkout button to your html

14. write another function at the bottom 
function checkout (set the cart equal to empty aray to gt a blank cart)

15. 
