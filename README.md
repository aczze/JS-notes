# JS-notes

how to make alert to site :
<!DOCTYPE html>
<html>
<head>
<title></title>
</head>
<body>
<script>
	alert("Krzysiek I");
</script>


</body>
</html>


How to attach an javascript to html file:
<script src = "js/main.js"></script>

furthermore in main.js file the content is :
alert("Krzys");
document.body.innerHTML = "This is some content";

Whether I want to write something in document use "document.write" or make some statements I do this :
document.body.innerHTML = "This is some content ";
var person = "Marcin";
var woman = "Andy";
if(person == "Daniel")
{alert("The variable person is fine");}

document.write (person);
document.write (" has pro skills")

In javaScript we are able to make an array which contains different variable types as elements! wowz :
var person = {name:"Marcin", numberOfLegs:"3", secondName "Maciej"};

If I want to create an function, and induce it I type :
function myScript()
{
  document.write (" This is the function");
}
myScript();

There is slightly difference beetween ++5 and 5++.

If I want to induce some event on click using java script then :
<body>
<p onclick = "myScript()">Clickme!</p>
</body>
function myScript()
{
document.write ("clicked");
}

Assignment operator :

var number = 10;
number *= 5;
50

Interesting usage of string :

var tactic = 1337;
var string = "This is the " + tactic + " we can win this in " + 5 + " seconds";
document.write(string);
This is the 1337 we can win this in 5 seconds. 

Making some conditions :

var tactic = 1337;
var string = "This is the " + tactic + " we can win this in " + 5 + " seconds.";

var number1 = 1000;
var number2 = 337;
var typeOfNumber = 1;

if(number1 + number2 == 1337 || number2 > 387) // || OR. && AND
{
  document.write(string);//in this case it will print.
}
else if (number1 + number2 != 1337 && number1 + number2 === typeOfNumber)
{
    document.write("The number1 and number2 does not equal 1337. :c");
}
else {
  document.write("There's no number");
}
Whether the number1 and number2 is integer, there will print if and else if.
But If number1 and number2 is string or something else there will print :
else {
  document.write("There's no number");
}

