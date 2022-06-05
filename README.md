
<HTML>

<HEAD>

<meta charset="UTF-8" />
<meta http-equiv="X-UA-Compatible" content="IE=edge" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />


<TITLE>
TechCalcy
</TITLE>

<script>


         //function that display value 
         function dis(val) 
         { 
             document.getElementById("result").value+=val 
         } 
           
         //function that evaluates the digit and return result 
         function solve() 
         { 
             let x = document.getElementById("result").value 
             let y = eval(x) 
             document.getElementById("result").value = y 
         } 
           
         //function that clear the display 
         function clr() 
         { 
             document.getElementById("result").value = "" 
         } 
      </script> 
      <!-- for styling -->
      <style> 
         .title{ 
         margin-bottom: 10px; 
         text-align:center; 
         width: 750px; 
         color:red; 
         border: solid orange 7px; 
         } 
  
         input[type="button"] 
         { 
         background-color:; 
         color:black; 
       
         border: solid blue 4px; 
         width:100%;
         height:50%
         } 
  
     
         input[type="text"] 
         { 
         background-color:white; 
         border:solid silver 5px; 
         width:100%;
         height:70%
         } 

      </style> 

   </head> 
   <!-- create table -->




<BODY background="m.jfif">
<H2><MARQUEE BGCOLOR = "YELLOW"> You are Good Friend and we Welcome you to TechCalcy.</MARQUEE></H2>




<CENTER>


    <div class = title ><h1><b>TechCalcy-Grow With Rohit</b></h1></div> 
      <table border="7" Width="700" height="700" CELLPADDING="10" CELLSPACING="10"> 
         <tr> 
           <td colspan="3"> <input type="text" id="result"/></td> 
            <!-- clr() function will call clr to clear all value -->
            <td><input type="button" value="c" onclick="clr()"/> </td> 
         </tr> 
         <tr> 
            <!-- create button and assign value to each button -->
            <!-- dis("1") will call function dis to display value -->
            <td> <input type="button" value="1" onclick="dis('1')"/> </td> 
            <td><input type="button" value="2" onclick="dis('2')"/> </td> 
            <td><input type="button" value="3" onclick="dis('3')"/> </td> 
            <td><input type="button" value="/" onclick="dis('/')"/> </td> 
         </tr> 
         <tr> 
           <td> <input type="button" value="4" onclick="dis('4')"/> </td> 
            <td><input type="button" value="5" onclick="dis('5')"/> </td> 
            <td><input type="button" value="6" onclick="dis('6')"/> </td> 
            <td><input type="button" value="-" onclick="dis('-')"/> </td> 
         </tr> 
         <tr> 
            <td><input type="button" value="7" onclick="dis('7')"/> </td> 
            <td><input type="button" value="8" onclick="dis('8')"/> </td> 
            <td><input type="button" value="9" onclick="dis('9')"/> </td> 
            <td><input type="button" value="+" onclick="dis('+')"/> </td> 
         </tr> 
         <tr> 
            <td><input type="button" value="." onclick="dis('.')"/> </td> 
            <td><input type="button" value="0" onclick="dis('0')"/> </td> 
            <!-- solve function call function solve to evaluate value -->
            <td><input type="button" value="=" onclick="solve()"/> </td> 
            <td><input type="button" value="*" onclick="dis('*')"/> </td> 
         </tr> 
      </table> 

<HR><HR>
<br>
<Pre>
<h2><B>
We always want to serve you to provide the best Experince. 
      To fulfill this we need your Suggestion. 
    Please message us on Twitter<A HREF="https://mobile.twitter.com/Rohitishere7"> Click here </A></B>
</h2>
</Pre>


</CENTER>

</BODY>


</HTML>
