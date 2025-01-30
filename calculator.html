<!DOCTYPE html>
<html>
  <head>
   <title>Calculator</title>
   <style>
    body {
      background-color: rgb(111, 111, 232);
      display: flex;
      justify-content: center;
      align-items:center;
      margin-top: 90px;
    }
   </style>
  </head>
  <body>
    <style>
     .calculator-container {
      background-color: rgb(218, 209, 237);
      display: grid;
      grid-template-columns: 2fr;
      width: 280px;
      height: 480px;
      border-radius: 3px;
     }
     .calculator-box {
      display: grid;
      grid-template-columns: 2fr;
     }
     .text-area {
      display: flex;
      justify-content: center;
      align-items: center;
      padding-top: 10px;
      height: 50px;
      padding-top: 35px;
     }
     .buttons {
      display: grid;
      padding-top: 0px;
      margin-bottom: 8px;  
     }
     .row1 {
      display: grid;
      grid-template-columns: repeat(4,1fr);
      margin-left: 9px;
      align-items: center;
      justify-content: center;
     }
     .row2 {
      display: grid;
      grid-template-columns: repeat(4,1fr);
      margin-left: 9px;
      align-items: center;
      justify-content: center;
      padding-top: 10px;
     }
     .row3 {
      display: grid;
      grid-template-columns: repeat(4,1fr);
      margin-left: 9px;
      align-items: center;
      justify-content: center;
      padding-top: 10px;
     }
     .row4 {
      display: grid;
      grid-template-columns: repeat(4,1fr);
      margin-left: 9px;
      align-items: center;
      justify-content: center;
      padding-top: 10px;
     }
     .row5 {
      display: grid;
      grid-template-columns: 1fr 1fr 2fr;
      margin-left: 9px;
      align-items: center;
      justify-content: center;
      padding-top: 10px;
     }
     .text {
      height: 80px;
      width: 250px;
      font-family: arial;
      font-weight: bold;
      font-size: 29px;
      display: flex;
      text-align: right;
      padding-right: 5px;
      padding-bottom: 10px;
      align-items: flex-end;
      justify-content: flex-end;
      position: relative;
      background-color: transparent;
      color: rgb(85, 85, 109);
      border: none;
      margin-top: 80px;
     }
     .text:focus {
      border: none !important;
      box-shadow: none;
      transition: border 0.2s ease-in-out;
      outline: none;
     }
     button {
      height: 50px;
      width: 57px;
      background-color: rgb(111, 111, 232);
      border: none;
      border-radius: 3px;
      color: rgb(218, 209, 237);
      font-size: 16px;
      transition: opacity 0.1s;
     }
     button:hover {
      opacity: 0.89;
     }
     button:active {
      opacity: 0.82;
     }
     .equal {
      text-align: center;
     }
     .equal_to {
      width: 125px;
      margin-right: 11px;
     }
    </style>  
   <div class="calculator-container">
    <div class="calculator-box">
     <div class="text-area">
      <input class="text" type="text" id="display" disabled>
     </div>
     <div class="buttons">
      <div class="row1">
        <div class="clear_button">
          <button onclick="clearDisplay()" class="ac">AC</button>
        </div>
        <div class="del_button">
          <button onclick="deleteLast()" class="de">DE</button>
        </div>
        <div class="decimal_button">
          <button onclick="appendToDisplay('.')" class="point"> . </button>
        </div>
        <div class="divide_button">
          <button onclick="appendToDisplay('/')" class="/">/</button>
        </div>
      </div>
      <div class="row2">
          <div class="seven">
            <button onclick="appendToDisplay('7')" class="7">7</button>
          </div>
          <div class="eight">
            <button onclick="appendToDisplay('8')" class="8">8</button>
          </div>
          <div class="nine">
            <button onclick="appendToDisplay('9')" class="9">9</button>
          </div>
          <div class="multiply">
            <button onclick="appendToDisplay('x')" class="x">x</button>
          </div>
      </div>
      <div class="row3">
        <div class="four">
          <button onclick="appendToDisplay('4')"class="4">4</button>
        </div>
        <div class="five">
          <button onclick="appendToDisplay('5')"class="5">5</button>
        </div>
        <div class="six">
          <button onclick="appendToDisplay('6')" class="6">6</button>
        </div>
        <div class="substract">
          <button onclick="appendToDisplay('-')" class="-">-</button>
        </div>
      </div>
      <div class="row4">
        <div class="one">
          <button onclick="appendToDisplay('1')" class="1">1</button>
        </div>
        <div class="two">
          <button onclick="appendToDisplay('2')" class="2">2</button>
        </div>
        <div class="three">
          <button onclick="appendToDisplay('3')" class="3">3</button>
        </div>
        <div class="addition">
          <button onclick="appendToDisplay('+')" class="+">+</button>
        </div></div>
      <div class="row5">
        <div class="double_zero">
          <button onclick="appendToDisplay('00')" class="00">00</button>
        </div>
        <div class="zero">
          <button onclick="appendToDisplay('0')" class="0">0</button>
        </div>
        <div class="equal">
          <button onclick="calculateResult('=')" class="equal_to">=</button>
        </div>
      </div>
      </div>
     </div>
    </div>
   </div>
   <script>
    // Function to append value to display
function appendToDisplay(value) {
  const display = document.getElementById("display");
  
  // Prevent entering two operators in a row
  if (/[+\-/]$/.test(display.value) && /[+\-/]/.test(value)) {
    return;
  }
  
  // Allow appending '.' only if there's no '.' already
  if (value === '.' && display.value.includes('.')) {
    return;
  }

  // Append the value
  display.value += value;
}

// Function to clear the display
function clearDisplay() {
  document.getElementById("display").value = "";
}

// Function to delete the last character from the display
function deleteLast() {
  let display = document.getElementById("display");
  display.value = display.value.slice(0, -1);
}

// Function to calculate the result of the expression
function calculateResult() {
  const display = document.getElementById("display");
  const expression = display.value.trim();

  // Check if the expression is empty or ends with an operator
  if (expression === "" || /[+\-*/.]$/.test(expression)) {
    display.value = "";
    return;
  }

  try {
    // Safely evaluate the expression
    const result = evaluateExpression(expression);
    display.value = result;
  } catch (error) {
    display.value = "Error"; // Display error if the expression is invalid
  }
}

// Function to safely evaluate the mathematical expression
function evaluateExpression(expression) {
  // Replace x with * and handle the rest of the operations
  expression = expression.replace(/x/g, '*').replace(/÷/g, '/');

  // Create a function and return the evaluated result
  return new Function('return ' + expression)();
}
   </script>
  </body>
</html>
