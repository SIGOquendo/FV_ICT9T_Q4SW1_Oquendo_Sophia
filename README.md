<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Q4SW1</title>
	<style>
	h1 {
		text-align: center;
	}
    td {
      background-color: rgb(188, 196, 250, 1.0);
      border: 10px solid lavender;
    }
    p {
      text-align: center;
    }
    table {
      text-align: center;
    }
    body {
			background-color: rgb(254, 245, 207, 1.0);
		}
  </style>
</head>
<body>
	<center>
	<table>
		<tr>
			<td colspan="2"><h1>Money Conversion</h1></td>
		</tr>
		<tr>
			<td colspan="2"><p>Choose Currency:</p></td>
		</tr>
		<tr>
			<td><button type="button" class="btn btn-primary" ><a href="page1.html">Dollar</a></button></td>
			<td><button type="button" class="btn btn-primary" ><a href="page2.html">Yen</a></button></td>
		</tr>
	</table>
</center>
</body>
</html>

<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Dollar</title>
	<style>
    td {
      background-color: rgb(188, 196, 250, 1.0);
      border: 10px solid lavender;
    }
    p {
      text-align: center;
    }
    table {
      text-align: center;
    }
    body {
			background-color: rgb(254, 245, 207, 1.0);
		}
  </style>
</head>
<body>
	<center>
	<table>
		<tr>
			<td><p>Pesos</p></td>
			<td><p>Dollars</p></td>
		</tr>
		<tr>
			<td colspan="2"><p>These prices are as of April 2, 2022</p></td>
		</tr>
		<tr>
			<td><p>1</p></td>
			<td><p id="a">a</p></td>
		</tr>
		<tr>
			<td><p>10</p></td>
			<td><p id="b">b</p></td>
		</tr>
		<tr>
			<td><p>25</p></td>
			<td><p id="c">c</p></td>
		</tr>
		<tr>
			<td><p>50</p></td>
			<td><p id="d">d</p></td>
		</tr>
		<tr>
			<td><p>100</p></td>
			<td><p id="e">e</p></td>
		</tr>
		<tr>
			<td colspan="2"><button type="button" class="btn btn-primary" ><a href="Index.html">go back</a></button></td>
		</tr>
	</table>
	<script>
		let a, b, c, d, e, f, g, h, i, j, k, l;
		a = 0.018; // Conversion rate
		b = 1; // values b to f are all pesos
		c = 10;
		d = 25;
		e = 50; 
		f = 100;
		g = a*b; // values g to k are all the converted values
		h = a*c;
		i = a*d;
		j = a*e;
		k = a*f;
		document.getElementById("a").innerHTML=g;
		document.getElementById("b").innerHTML=h;
		document.getElementById("c").innerHTML=i;
		document.getElementById("d").innerHTML=j;
		document.getElementById("e").innerHTML=k;
	</script>
</center>
</body>
</html>

<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Yen</title>
	<style>
    td {
      background-color: rgb(188, 196, 250, 1.0);
      border: 10px solid lavender;
    }
    p {
      text-align: center;
    }
    table {
      text-align: center;
    }
    body {
			background-color: rgb(254, 245, 207, 1.0);
		}
  </style>
</head>
<body>
	<center>
	<table>
		<tr>
			<td><p>Pesos</p></td>
			<td><p>Yen</p></td>
		</tr>
		<tr>
			<td colspan="2"><p>These prices are as of April 2, 2022</p></td>
		</tr>
		<tr>
			<td><p>1</p></td>
			<td><p id="a">a</p></td>
		</tr>
		<tr>
			<td><p>10</p></td>
			<td><p id="b">b</p></td>
		</tr>
		<tr>
			<td><p>25</p></td>
			<td><p id="c">c</p></td>
		</tr>
		<tr>
			<td><p>50</p></td>
			<td><p id="d">d</p></td>
		</tr>
		<tr>
			<td><p>100</p></td>
			<td><p id="e">e</p></td>
		</tr>
		<tr>
			<td colspan="2"><button type="button" class="btn btn-primary" ><a href="Index.html">go back</a></button></td>
		</tr>
	</table>
</center>
	<script>
		let a, b, c, d, e, f, g, h, i, j, k, l;
		a = 2.70; // Conversion rate
		b = 1; // values b to f are all pesos
		c = 10;
		d = 25;
		e = 50; 
		f = 100;
		g = a*b; // values g to k are all the converted values
		h = a*c;
		i = a*d;
		j = a*e;
		k = a*f;
		document.getElementById("a").innerHTML=g;
		document.getElementById("b").innerHTML=h;
		document.getElementById("c").innerHTML=i;
		document.getElementById("d").innerHTML=j;
		document.getElementById("e").innerHTML=k;
	</script>
</body>
</html>
