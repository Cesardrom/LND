# Tarea FLOAT

<br>

### Codigo del html

<br>

---

```html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" lang="es" xml:lang="es">
	<head>
		<meta http-equiv="Content-Type" content="text/html; charset=UTF-8" />
		<meta name="author" content="Cesar Dominguez Romero"/>
		<title></title>
		<link rel="stylesheet" href="./Estilos/Index.css">
	</head>
	<body>

		<div class="contenedor">
			<img class="imagen" src="./Imagenes/iespuerto.png" alt="Logo Puerto Cruz" />
			<p> Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
			tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
			quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
			consequat. 
			</p>
			<p> Duis aute irure dolor in reprehenderit in voluptate velit esse
			cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
			proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
			</p>
			<p> Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
			tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
			quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
			consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
			cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
			proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
			</p>
			<p class="letraCapital"> Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
			tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
			quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
			consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
			cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
			proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
			</p>
		</div>



	</body>
</html>
```
---

<br>

### Codigo del CSS

<br>

---
```css
			img {
				float: left;
				margin: 5px;
			}

			.contenedor {
				width: 550px;
				font-family: Verdana, Arial;
				background-color: orange;
				border: 15px outset gray;
				text-align: justify;
				padding: 10px;
			}

			.letraCapital:first-letter {
				font-family: Times;
				color: gray;
				font-size: 60px;
				float: left;
				border: 1px solid black;
				margin: 5px;
			}

			p:not(.letraCapital) {
				text-indent: 30px;
			}
```
---

<br>

## Resultado final

<br>

---

<img src="./Imagenes/2024-05-14_15-05_1.png"/>