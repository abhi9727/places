<!DOCTYPE html>
<html>
<head>
  <title>Calculator</title>
  <link rel="stylesheet" type="text/css" href="style.css">
 
</head>
<body>
    <div class = "container">

        <div class="calculator">
            <input type="text" id="display" disabled>
            <div class="keypad">
                <button onclick="clearDisplay()">C</button>
                <button onclick="appendToDisplay('7')">7</button>
                <button onclick="appendToDisplay('8')">8</button>
                <button onclick="appendToDisplay('9')">9</button>
                <button onclick="appendToDisplay('/')">/</button>
                <button onclick="appendToDisplay('4')">4</button>
      <button onclick="appendToDisplay('5')">5</button>
      <button onclick="appendToDisplay('6')">6</button>
      <button onclick="appendToDisplay('*')">*</button>
      <button onclick="appendToDisplay('1')">1</button>
      <button onclick="appendToDisplay('2')">2</button>
      <button onclick="appendToDisplay('3')">3</button>
      <button onclick="appendToDisplay('-')">-</button>
      <button onclick="appendToDisplay('0')">0</button>
      <button onclick="appendToDisplay('.')">.</button>
      <button onclick="calculate()">=</button>
      <button onclick="appendToDisplay('+')">+</button>
      <button onclick="backspace()">B S</button>
      
      
    </div>
</div>

</div>
  <script src="script.js"></script>
</body>
</html>
