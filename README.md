# Calculator
<html>
    <head>
        
        <meta name="msapplication-tap-highlight" content="no" />
		<meta name="viewport" content="width=500, initial-scale=1">
        <!-- WARNING: for iOS 7, remove the width=device-width and height=device-height attributes. See https://issues.apache.org/jira/browse/CB-4323 -->

        <link rel="stylesheet" type="text/css" href="css/index.css" />
        <title>Calculator</title>
    </head>
    <body>
        <form Name="calc">
<table border=2>
<tr>
<td colspan=4><input type=text Name="display"></td>
</tr>
<tr>
<td><input type=button value="0" OnClick="calc.display.value+='0'"></td>
<td><input type=button value="1" OnClick="calc.display.value+='1'"></td>
<td><input type=button value="2" OnClick="calc.display.value+='2'"></td>
<td><input type=button value="+" OnClick="calc.display.value+='+'"></td>
</tr>
<tr>
<td><input type=button value="3" OnClick="calc.display.value+='3'"></td>
<td><input type=button value="4" OnClick="calc.display.value+='4'"></td>
<td><input type=button value="5" OnClick="calc.display.value+='5'"></td>
<td><input type=button value="-" OnClick="calc.display.value+='-'"></td>
</tr>
<tr>
<td><input type=button value="6" OnClick="calc.display.value+='6'"></td>
<td><input type=button value="7" OnClick="calc.display.value+='7'"></td>
<td><input type=button value="8" OnClick="calc.display.value+='8'"></td>
<td><input type=button value="x" OnClick="calc.display.value+='*'"></td>
</tr>
<tr>
<td><input type=button value="9" OnClick="calc.display.value+='9'"></td>
<td><input type=button value="C" OnClick="calc.display.value=''"></td>
<td><input type=button value="=" OnClick="calc.display.value=eval(calc.display.value)"></td>
<td><input type=button value="/" OnClick="calc.display.value+='/'"></td>
</tr>
</table>
</form>
        <script type="text/javascript" src="cordova.js"></script>
        <script type="text/javascript" src="js/index.js"></script>
        <script type="text/javascript">
            app.initialize();
        </script>
    </body>
</html>
