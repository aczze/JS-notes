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
