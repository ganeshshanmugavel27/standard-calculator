# Design of a Standard Calculator

Step 1:
Clone the repository from Github.

Step 2:
Start a django project and make necessary changes

Step 3:
Create HTML, CSS and JAVASCRIPT program for the calculator

Step 4:
CSS for design and JavaScript for the calculator

Step 5:
Validate HTML, CSS and JavaScript code.

Step 6:
Validate the HTML and CSS code.

Step 7:
Publish your URL and test the Calculator

PROGRAM :
HTML

<title>Calculator</title>
Calculator
(	)	C	%
7	8	9	X
4	5	6	-
1	2	3	+
0	.	/	=
<script src="/static/JS/index.js"></script> CSS .container{ text-align: center; margin-top:23px } table{ margin: auto; } input{ border-radius: 21px; border: 5px solid #0328f8; font-size:34px; height: 65px; width: 456px; } button{ border-radius: 20px; font-size: 40px; background: #f8f8f8; width: 102px; height: 90px; margin: 6px; } .calculator{ border: 4px solid #1ae608; background-color: #000000; padding: 23px; border-radius: 53px; display: inline-block;
} h1{ OUTPUT: h1{ font-size: 28px; font-family: 'Courier New', Courier, monospace; } JavaScript let screen = document.getElementById('screen'); buttons = document.querySelectorAll('button'); let screenValue = ''; for (item of buttons) { item.addEventListener('click', (e) => { buttonText = e.target.innerText; console.log('Button text is ', buttonText); if (buttonText == 'X') { buttonText = '*'; screenValue += buttonText; screen.value = screenValue; } else if (buttonText == 'C') { screenValue = ""; screen.value = screenValue; } else if (buttonText == '=') { screen.value = eval(screenValue); } else { screenValue += buttonText; screen.value = screenValue; } }) }


## OUTPUT:
![ganesh ex 08](https://github.com/ganeshshanmugavel27/standard-calculator/assets/122046208/ab69dbf5-f1ec-43d4-85eb-8b22d899fb76)


## Result:
program executed successfully 
