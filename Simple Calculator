<!DOCTYPE html>
<html>
<head>
    <title>Simple Calculator</title>
    <style>
        .calculator {
            width: 500px;
            margin: 2px;
            padding: 1px;
            border: 3px solid #ccc;
            border-radius: 1px;
            box-shadow: 0px 0px 10px #212020;
            background-color: gray;
            
            
        }

        input[type="text"], input[type="button"] {
            width: 100px;
            height: 100px;
            font-size: 20px;
            margin: 1px;
            
        }
        
        </style>
</head>
<body>
    <div class="calculator">
        <input type="text" id="display" readonly style="width:8.1cm; background-color: white;">
        <input type="button" value="AC" onclick="clearDisplay()" style="background-color: rgb(76, 118, 76);">
        <input type="button" value="9" onclick="appendToDisplay('9')">
        <input type="button" value="8" onclick="appendToDisplay('8')">
        <input type="button" value="7" onclick="appendToDisplay('7')">
        <input type="button" value="+" onclick="appendToDisplay('+')"style="backgroung-colo:gray;">
        <input type="button" value="4" onclick="appendToDisplay('4')">
        <input type="button" value="5" onclick="appendToDisplay('5')">
        <input type="button" value="6" onclick="appendToDisplay('6')">
        <input type="button" value="-" onclick="appendToDisplay('-')">
        <input type="button" value="1" onclick="appendToDisplay('1')">
        <input type="button" value="2" onclick="appendToDisplay('2')">
        <input type="button" value="3" onclick="appendToDisplay('3')">
        <input type="button" value="*" onclick="appendToDisplay('*')">
        <input type="button" value="." onclick="appendToDisplay('.')">
        <input type="button" value="0" onclick="appendToDisplay('0')">
        <input type="button" value="=" onclick="calculate()">
        <input type="button" value="/" onclick="appendToDisplay('/')">
    </div>

    <script>
        function appendToDisplay(value) {
            document.getElementById('display').value += value;
        }

        function clearDisplay() {
            document.getElementById('display').value = '';
        }

        function calculate() {
            var display = document.getElementById('display').value;
            try {
                var result = eval(display);
                document.getElementById('display').value = result;
            } catch (error) {
                document.getElementById('display').value = 'Error';
            }
        }
    </script>
</body>
</html>
