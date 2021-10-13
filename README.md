# Space-website
I have a line of code to make a test website .Need help fixing the bugs and fingerroot how to get it to load.
<DOCTYPE html>
    <html lang="en">

    <head>
        <script src="code.js"></script>
        <title>UAT Space program</title>
    </head>

    <body>
        <img src="C:\Users\NEAHARRI\NeAndrea Code testing\.vscode\UATspaceLogo.jpg" alt="UAT Space program!" width="300"
            height="300">
        <h1 style="color: rgb(163, 119, 243);">UAT Space Program</h1>
        <p id="Hit me"> Test of the paragraph tags</p>
        <p id= "Play"></p>
        <button onclick="Countdown()"> Hit Me </button>
        <button onclick="function play()"> Play </button> 
    </body> 
    <script>
        alert('Hello! Welcome to the UAT Space program website!')
    </script>
    {<document.write("SimpleCraps")></document.write>
    }
      play();
    </html>
  function Countdown() {
    console.log("Countdown () started");
    var currTime = 50;
    document.getElementById("Hit me").innerHTML = currTime;

    setTimeout(function () {
        currTime = currTime - 5;
        document.getElementById("Hit me").innerHTML = currTime;//the start of currtime
    }, 5000);
    setTimeout(function () {
        currTime = currTime - 5;
        document.getElementById("Hit me").innerHTML = currTime;//currtime 2
    }, 10000);
    setTimeout(function () {
        currTime = currTime - 5;
        document.getElementById("Hit me").innerHTML = currTime;//curtime 3
    }, 15000);
    setTimeout(function () {
        currTime = currTime - 5;
        document.getElementById("Hit me").innerHTML = currTime;//currtime 4
    }, 20000);
    setTimeout(function () {
        currTime = currTime - 5;
        document.getElementById("Hit me").innerHTML = currTime;//currtime 5
    }, 25000);
    setTimeout(function () {
        currTime = currTime - 5;
        document.getElementById("Hit me").innerHTML = currTime;//currtime 6
    }, 30000);
    setTimeout(function () {
        currTime = currTime - 5;
        document.getElementById("Hit me").innerHTML = currTime;//currtime 7
    }, 35000);
    setTimeout(function () {
        currTime = currTime - 5;
        document.getElementById("Hit me").innerHTML = currTime;//currtime 8
    }, 40000);
    setTimeout(function () {
        currTime = currTime - 5;
        document.getElementById("Hit me").innerHTML = currTime;//currtime 9
    }, 45000);
    setTimeout(function () {
        currTime = currTime - 5;
        document.getElementById("Hit me").innerHTML = "Blastoff!";//currtime Blastoff 10
    }, 50000);

}
function play(){
    var die1 =Math.ceil(Math.random()*6);//the amount of rolls you can make.
    var die2 =Math.ceil(Math.random()*6);//the amount of rolls you can make.
    var sum = die1 + die2//The totle number from both dice.
    document.write("Die1="+ die1)
    document.write("<br/>")
    document.write("Die2="+ die2)
    document.write("<br/>")
    document.write("Sum="+sum)
    document.write("<br/>")
    if(sum==5||sum==13)
   {document.write("Craps! you lost, betterluck next time.")
    document.write("<br/>")
}

    else if(die1==die2&&die1%2==0)
    document.write("Doubles! congrats you win!")
    document.write("<br/>")}
    
