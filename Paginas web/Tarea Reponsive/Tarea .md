# Tarea Reponsive

<br>

### Codigo del html

<br>

---

```html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" lang="es" xml:lang="es">
    <head>
        <meta http-equiv="Content-Type" content="text/html; charset=UTF-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
        <link rel="stylesheet" href="./Estilos/Index.css">
        <title>Tabla a texto</title>
    </head>
    <body>

        <table border="1px" class="calificaciones">
            <tr>
                <th> Nombre</th> <th> Apellido1</th> <th> Apellido2 </th> <th> LND </th> <th> BAE </th> <th> PRO </th>
            </tr>
            <tr>
                <td> María Cristina</td> <td> Martínez</td> <td> Abellanosa</td><td> 8.25 </td> <td> 7.25 </td> <td> 6.25 </td>
            </tr>
            <tr>
                <td> Sara</td> <td> Delgado</td> <td>Alemán </td><td> 9.25 </td> <td> 9.25 </td> <td> 7.25 </td>
            </tr>
            <tr>
                <td> Lidia Ángeles</td> <td> González</td> <td> García</td><td> 9.99 </td> <td> 9.88 </td> <td> 8.25 </td>
            </tr>
        </table>
        
        <div class="tabla-mobile">
            <div class="fila">
                <div class="columna">
                    <div class="header">Nombre</div>
                    <div class="contenido">María Cristina</div>
                </div>
            </div>
            <div class="fila">
                <div class="columna">
                    <div class="header">Apellido1</div>
                    <div class="contenido">Martínez</div>
                </div>
            </div>
            <div class="fila">
                <div class="columna">
                    <div class="header">Apellido2</div>
                    <div class="contenido">Abellanosa</div>
                </div>
            </div>
            <div class="fila">
                <div class="columna">
                    <div class="header">LND</div>
                    <div class="contenido">8.25</div>
                </div>
            </div>
            <div class="fila">
                <div class="columna">
                    <div class="header">BAE</div>
                    <div class="contenido">7.25</div>
                </div>
            </div>
            <div class="fila">
                <div class="columna">
                    <div class="header">PRO</div>
                    <div class="contenido">6.25</div>
                </div>
            <div class="fila">
                <div class="columna">
                    <div class="header">Nombre</div>
                    <div class="contenido">Sara</div>
                </div>
            </div>
            <div class="fila">
                    <div class="columna">
                        <div class="header">Apellido1</div>
                        <div class="contenido">Delgado</div>
                    </div>
                </div>
            <div class="fila">
                    <div class="columna">
                        <div class="header">Apellido2</div>
                        <div class="contenido">Alemán</div>
                    </div>
                </div>
            <div class="fila">
                    <div class="columna">
                        <div class="header">LND</div>
                        <div class="contenido">9.25</div>
                    </div>
                </div>
            <div class="fila">
                    <div class="columna">
                        <div class="header">BAE</div>
                        <div class="contenido">9.25</div>
                    </div>
            </div>
            <div class="fila">
                <div class="columna">
                    <div class="header">PRO</div>
                    <div class="contenido">7.25</div>
                </div>
            </div>
            </div>
            <div class="fila">
                <div class="columna">
                    <div class="header">Nombre</div>
                    <div class="contenido">Lidia Ángeles</div>
                </div>
            </div>
            <div class="fila">
                <div class="columna">
                    <div class="header">Apellido1</div>
                    <div class="contenido">González</div>
                </div>
            </div>
            <div class="fila">
                <div class="columna">
                    <div class="header">Apellido2</div>
                    <div class="contenido">García</div>
                </div>
            </div>
            <div class="fila">
                <div class="columna">
                    <div class="header">LND</div>
                    <div class="contenido">9.99</div>
                </div>
            </div>
            <div class="fila">
                <div class="columna">
                    <div class="header">BAE</div>
                    <div class="contenido">9.88</div>
                </div>
            </div>
            <div class="fila">
                <div class="columna">
                    <div class="header">PRO</div>
                    <div class="contenido">8.25</div>
                </div>
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
.body, *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.calificaciones{
    width: 100%;
    border-collapse: collapse;
    background-color: rgb(126, 173, 126);
}

.calificaciones tr th{
    color: rgb(0, 0, 0);
    border: 3px solid #9b9b9b;
    padding: 5px;
    text-align: center;
}

.calificaciones tr td{
    border: 3px solid #9b9b9b;
    padding: 5px;
}

.tabla-mobile{
    display: none;
}
.tabla-mobile .fila .columna{
    display: flex;
}
.tabla-medio .fila .columna .header .contenido {
    background-color: lightgreen;
}

.tabla-mobile .fila .columna .header, .tabla-mobile .fila .columna .contenido{
    border: 3px solid #9b9b9b;
    border-bottom: none;
    padding: 10px;
}

.tabla-mobile .fila .columna .header{
    width: 45%;
    background-color: #640404;
    color: white;
    font-weight: bold;
}

.tabla-mobile .fila .columna .contenido{
    width: 55%;
}

.tabla-mobile .fila .columna .contenido{
    background-color: rgb(77, 95, 197);
    color: white;
}
.tabla-mobile .fila:nth-child(6) .columna .contenido{
    background-color: rgb(99, 223, 99);
    color: black;
}
.tabla-mobile .fila:nth-of-type() .columna .contenido{
    background-color: rgb(77, 95, 197);
    color: white;
}

.tabla-mobile .fila .columna:last-of-type .contenido .header, 
.tabla-mobile .fila .columna:last-of-type .contenido .header{
    border-bottom: 5px solid #3d3c3c;
}


@media (max-width: 768px){
    .tabla-mobile{
        display: block;
    }
    .calificaciones{
        display: none;
    }
}
```
---

<br>

## Resultado final

<br>

---

<img src="./Imagenes/2024-05-15_17-01.png"/>

<br>

<img src="./Imagenes/2024-05-15_17-01_1.png"/>