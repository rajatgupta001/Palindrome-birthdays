keep <script src="app.js"></script> inside body and do not add type="text/script"

In order to reverse a string, we need to perform the following steps:

break the string into an array: break = string.split("");
reverse the array: reversedarray = break.reverse()
join the array elements: reversedarray.join("") 


if we add an string and an number the output is auto converted into string. for Example: 4 + "4" = "44"
other way to convert into string: number.toString()


slice method:
let str = "Hello world!";
str.slice(0, 5)   // Returns "Hello"

This method can also be used to get last 2 digits of year(must be string):
"2011".slice(-2)  //returns "11"

remember that JS cannot return more than 1 variable therefore in general we return a list or dictionary(if required)

remember leap year function.