# Java Script
- case sensitive



## adding strings
- when we write '$'+433+21 we generally expect its result to be $456 but...since the first $ which is string, it converts 433 to string and these both convert 21 to string and the result will be <font style="color:red">$43321</font>
- To fix this : use round brackets to add those numbers and then concatenate it with $             
- Concatenation is basically adding of two strings
- Example for the above mentioned problem: let us say printing of the string    <font style="color:yellow">items(2): $30</font> and assume that we are adding 1 and 1  to get 2 in that bracket , so the solution would be:<font style="color:orange"> 'items('+(1+1)+'): $'+30</font>

<hr>
<h2>pop up: </h2>
we can use <font style="color:red">alert('string');</font> for popups or called as alert message...

<h2>using quotes for string :</h2>
- However its preferred to use single quotes since its easier to type and also for better readability,sometimes there may be a apostrophe in a string which is unclosed single quote ,for eg:<font style="color:yellow">I'm learning js</font>, here if we give <font style="color:orange">'I'm learning js'</font>,it will show error since it considers <font style="color:yellow">I</font> as string and <font style="color:orange"> m</font> as unexpected identifier since it doesn't possess any opening quote..

- To overcome this problem we can use double quotes..
- other method is using escape character i.e, in string using <font style="color:red">I\'</font>
- Here \' is treated as character not as any special symbol...
- other than these cases use single quote as default for convenience ...


<h3>Third way of  creating string: <font style="color:red">using backtick (`)</font><h3>


  - The difference is:
    - using backtick we can do interpolation
    - Interpolation is inserting values directly into string


- The string created using backtick is called as template string...
- <font style="color:yellow">Syntax of interpolation:</font>
  
     ${ }


  - Let us say we need to print :<font style="color:orange">items(2): $28.94 </font> adding 1 and 1 ,and addding 2095 cents with 799 cents 
   

       we can write :
       

           `items(${1+1}): $${(2095+799)/100}`

- Interpolation is much cleaner way of inserting values into string than concatenatio           

- <font style ="color:yellow">Other advantage of template string: </font>Creating multiline string 
     -  eg: 'some <font style="color:red">//press enter</font> text`
  

 <h2>What to do<h2>

   - use quotes by default and if u need interpolation and multiline string then go for template strings

  