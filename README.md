# Membuat kalkulator dengan javascript

1. Buat folder project terlebih dulu.
2. Download 2 file yg dibutuhkan yaitu :
   <a href="https://github.com/codemetik/calculator_math/blob/main/math.js">math.js</a>
   dan <a href="https://github.com/codemetik/calculator_math/blob/main/math.min.js">math.min.js</a>
3. Copy file yg sudah di download yaitu math.js dan math.min.js ke dalam folder project yang sudah dibuat pada langkah satu.
4. Selanjutnya didalam folder project buatlah sebuah file bernama index.html
5. berikut langkah-langkahnya :
   ## Buat struktur HTML dasar 
   ```html
   <!DOCTYPE html>
   <html>
   <head>
   	<meta charset="utf-8">
   	<meta name="viewport" content="width=device-width, initial-scale=1">
   	<title>Kalkulator Sederhana</title>
   	
   </head>
   <body>
   
   </body>
   </html>
   ```
   ## Sertakan file math.js dan math.min.js di bawah tag `<title></title>`
   ```html
   <script type="text/javascript" src="math.js"></script>
   <script type="text/javascript" src="math.min.js"></script>
   ```
   ## Buatlah struktur table di antara tag `<body></body>` untuk menampilkan tombol-tombol kalkulator
   ```html
   <h1>Membuat kalkulator sederhana dengan javascript</h1>
	<table id="calcu">
		<tr>
			<td colspan="3"><input type="text" id="result"></td>
			<td><input type="button" value="c" onclick="clr()"/></td>
		</tr>
		<tr>
			<td><input type="button" value="1" onclick="dis('1')" onkeydown="myFunction(event)"></td>
			<td><input type="button" value="2" onclick="dis('2')" onkeydown="myFunction(event)"></td>
			<td><input type="button" value="3" onclick="dis('3')" onkeydown="myFunction(event)"></td>
			<td><input type="button" value="/" onclick="dis('/')"></td>
		</tr>
		<tr>
			<td><input type="button" value="4" onclick="dis('4')" onkeydown="myFunction(event)"></td>
			<td><input type="button" value="5" onclick="dis('5')" onkeydown="myFunction(event)"></td>
			<td><input type="button" value="6" onclick="dis('6')" onkeydown="myFunction(event)"></td>
			<td><input type="button" value="*" onclick="dis('*')" onkeydown="myFunction(event)"></td>
		</tr>
		<tr>
			<td><input type="button" value="7" onclick="dis('7')" onkeydown="myFunction(event)"></td>
			<td><input type="button" value="8" onclick="dis('8')" onkeydown="myFunction(event)"></td>
			<td><input type="button" value="9" onclick="dis('9')" onkeydown="myFunction(event)"></td>
			<td><input type="button" value="-" onclick="dis('-')" onkeydown="myFunction(event)"></td>
		</tr>
		<tr>
			<td><input type="button" value="." onclick="dis('.')" onkeydown="myFunction(event)"></td>
			<td><input type="button" value="0" onclick="dis('0')" onkeydown="myFunction(event)"></td>
			<td><input type="button" value="+" onclick="dis('+')" onkeydown="myFunction(event)"></td>
			<td><input type="button" id="calcu" value="=" onclick="solve()"></td>
		</tr>
	</table>
   ```
   ## Styling element table agar menarik dengan CSS secara internal.
   ```html
   <style type="text/css">
		h1{
			text-align: center;
			text-decoration: underline;
		}
		table{
			border: 1px solid black;
			margin-left: auto;
			margin-right: auto;
		}

		input[type="button"]{
			width: 100%;
			padding: 20px 40px;
			background-color: green;
			color: white;
			font-size: 24px;
			font-weight: bold;
			border: none;
			border-radius: 5px;
		}

		input[type="text"]{
			padding: 20px 30px;
			font-size: 24px;
			font-weight: bold;
			border: none;
			border-radius: 5px;
			border: 2px solid black;
		}
	</style>
   ```
   ## Selanjutnya terapkan kode javascript berikut di bawah struktur elemen table.
   ```javascript
   ```
   ## Refresh web project nya.
   ## Selesai.
 
