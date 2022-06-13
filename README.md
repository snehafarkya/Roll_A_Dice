# Roll_A_Dice 
## Hey Everyone! Welcome on the board!
### This is a Dice rolling game made with python. It has unique task on every number.
 <b> Do check it out✨  
## Table of Contents: 
* About the Game
* Modules and Functionality 
* Connectivity with MySQL</mark> 

### <u> ***About the Game :*** </u>

<mark style="background: purple; color:white;padding:3px">Remember playing a rolling dice game in childhood? </mark> 
     We've all loved it when dice throws 6 because of the extra chance it gives!
     This game is all about remincing your childhood memories. This is made with python. 
   
Rules: 

   <code>1. You have to roll a dice. 
      2. Whatever number comes in, an associated task will be given to you. 
      3. You have to perform the task. 
      4. After you're done, press enter. 
      5. Don't forget to have fun🥳 </code> 

### <u> ***Modules and Functionality :*** </u> 

A <code style="background:skyblue;">Random</code> module is used here to choose a random number in the range og 1 to 6.  
Basically it will ask you your name. If you agree to play, press 1. Then, it wll randomly gives you a number and you have to perform the associated task! 
Meanwhile, if you press 2, you will exit from the game as the <code style="background:skyblue;">exit()</code> function comes into play. 

### <u> ***Connectivity with MySQL :*** </u> 

The most researching part of this game is <mark>How to connect MySQL database with Python.</mark> 
After googling it for almost 10 times, I finally found my answer🤩. 
Here is the code snippet: 

<code>import mysql.connector 
    mydb = mysql.connector.connect(
        host="localhost",
        user= "root",
        passwd= "yourpassword",
        database = "roll_a_dice_python"
)
mycursor = mydb.cursor()</code> 

Take a look at this video: 

  <video controls="true" >
    <source src="./Video.mp4" type="video/mp4" >
  </video>






