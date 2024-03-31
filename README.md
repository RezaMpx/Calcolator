# Calcolator
<!DOCTYPE html>
<html lang="fa" dir="rtl">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    
  </style>
</head>

<body>
<ul>
<li>
<p>This project is a simple calculator with basic operations of addition, subtraction, multiplication, and division.</p>
</li>
<li>
<p><strong>Installation and Setup</strong>: To use the calculator, clone the project from GitHub and run the index file.</p>
</li>
<li>
<p><strong>Usage</strong>: Input your desired numbers and select the operation you want to perform.</p>
</li>
</ul>
  <hr />
  <pre>
      <div class="calculator">
        <input type="text" id="display" disabled>
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
      </pre>
    </div>
</body>

</html>
