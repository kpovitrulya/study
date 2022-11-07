<!DOCTYPE html>
<!DOCTYPE html>
<html>
<head>
	
	<script>

	  function func1()
	    {
		var num11 = Number(document.getElementById("num11").value);
		var num21 = Number(document.getElementById("num21").value);
		ar plus = num11 + num21;
	  document.getElementById("plus").innerHTML = plus;
        }

      function func2()
        {
  	    var num12 = Number(document.getElementById("num12").value);
        var num22 = Number(document.getElementById("num22").value);
        var min = num12 - num22;
      document.getElementById("min").innerHTML = min;
        }

  	  function func3()
  	    {
        var num13 = Number(document.getElementById("num13").value);
        var num23 = Number(document.getElementById("num23").value);
        var pomn = num13 * num23;
      document.getElementById("pomn").innerHTML = pomn;
        }
  	  
  	  function func4()
  	    {
  		var num14 = Number(document.getElementById("num14").value);
  		var num24 = Number(document.getElementById("num24").value);
        var dil = num14 / num24;
      document.getElementById("dil").innerHTML = dil;
        }
      
      function func5()
        {
        var num15 = Number(document.getElementById("num15").value);
        var num25 = Number(document.getElementById("num25").value);
        var step =  Math.pow(num15, num25);
      document.getElementById("step").innerHTML = step;
        }

	</script>

</head>

<body>

<p>
<input id="num11"/> + <input id="num21"/> = <output id="plus"/>
<button onclick="func1()">Відповідь</button> 
</p>

<p>
<input id="num12"/> - <input id="numb22"/> = <output id="min"/>
<button onclick="func2()">Відповідь</button>
</p>

<p>
<input id="num13"/> * <input id="num23"/> = <output id="pomn"/>
<button onclick="func3()">Відповідь</button>
</p>

<p>
<input id="num14"/> / <input id="num24"/> = <output id="dil"/>
<button onclick="func4()">Відповідь</button>
</p>

<p>
<input id="num15"/> ^ <input id="numb25"/> = <output id="step"/>
<button onclick="func5()">Відповідь</button>
</p>

</body>
</html>
