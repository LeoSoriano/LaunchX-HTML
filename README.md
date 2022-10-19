# PRACTICA HTML
-----------------------------------------------------------------------------------------------------------------------------
Los siguientes codigos muestran las etiquetas mas basicas de HTMl y los elementos compuetsos más basicos que tiene HTML

---------------------------------------

# Etiquetas Basicas

<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE-edge">
        <meta name="viewpoet" content="width=device-width, initial-scale=1.0">
        <title>Practica 1 LaunchX</title>
    </head>
    <body>
        <!-- Headings -->
        <h1> Bienvenido a tu primera practica</h1>
        <h2>Bienvenidos Explorers</h2>

        <!-- Parrafos -->
        <p> Este es un parrafo para los explorers. Este es un parrafo para los explorers.Este es un parrafo para los explorers.
            Este es un parrafo para los explorers.Este es un parrafo para los explorers.</p>

        <p>Parrafo 2. Parrafo 2. Parrafo 2. Parrafo 2.</p>

        <!-- Links/Enlaces -->
        <a href="https://github.com/Launch-X-Latam" target="blank">Link a LaunchX</a>
        <br>

        <!-- Imagenes -->
        <img src="https://i.imgur.com/84QT6os.jpeg" alt="Perritos Lindos" width="350px" height="350px">

        <!-- Tablas -->
        <table>
            <tr>
                <th>Compañia</th>
                <th>Contacto</th>
                <th>Pais</th>
            </tr>
            <tr>
                <td>Telmex</td>
                <td>Raul Salinas</td>
                <td>Mexico</td>
            </tr>
            <tr>
                <td>TotalPlay</td>
                <td>Toni Gambino</td>
                <td>Italia</td>
            </tr>
        </table>

        <!-- Listas -->
        <ul>
            <li>Cafe</li>
            <li>Pan</li>
            <li>Huevos revueltos</li>
        </ul>

        <ol>
            <li>CPU</li>
            <li>Monitor</li>
            <li>Teclado</li>
        </ol>

        <dl>
            <dt>Enchiladas</dt>
            <dd>- Tortilla frita con salsa, rellena de pollo</dd>
            <dt>Molletes</dt>
            <dd>- Bolillo con frijoles y queso</dd>
        </dl>

    </body>

</html>

-------------------------------------------------------------------

# Elementos Compuestos

<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE-edge">
        <meta name="viewport" content="width-device-width, initial-scale=1.0">
        <title>ELEMENTOS COMPUESTOS</title>
    </head>
    <body>
        <h1>Explicacion de elementos compuestos LaunchX</h1>

        <!-- Labels / Etiquetas -->
        <label for="Input"> Ejemplo de Input de Texto</label>
        <br>
        <!-- Entradas / Inputs -->
        <input type="text" id="Input1" name="Input1">
        <br><br>

        <hr>
        <!-- Tipos de Inputs -->
        <h2>Input De Texto</h2>
        <label for="correo1">Input de Correo</label><br>
        <input type="email" id="correo1" name="correo1"><br><br>

        <label for="numero1">Input de numero</label><br>
        <input type="number" id="psw1" name="psw1"><br><br>

        <label for="tell">Input de Telefono</label><br>
        <input type="tell" id="tell" name="tell" maxlength="10"><br><br>

        <label for="urll">Input de URL</label><br>
        <input type="url" id="url1" name="url1"><br><br>

        <hr>

        <h2>Input de seleccion multiple</h2><br>
        <input type="checkbox" id="topping1" name="topping1" value="Cebolla">
        <label for="tooping1">Tacos de Cebolla</label><br>

        <input type="checkbox" id="tooping2" name="topping2" value="Cilantro">
        <label for="tooping2">Tacos de Cilantro</label><br>

        <input type="checkbox" id="topping3" name="tooping3" value="Salsa">
        <label for="tooping3">Tacos de Salsa</label><br><br>

        <h2>Input de seleccion unica</h2><br>
        <input type="radio" id="roja" name="salsas" value="Roja">
        <label for="roja">Roja</label><br>

        <input type="radio" id="verde" name="verde" value="Verde">
        <label for="verde">Verde</label><br>

        <input type="radio" id="guacamole" name="guacamole" value="Guacamole">
        <label for="guacamole">Guacamole</label><br>

        <h2>Select con Input</h2>
        <label for="refresco">Elige tu refresco favorito</label><br>
        <input list="refresco">
        <datalist id="refresco">
            <option value="Coca-Cola">
            <option value="Manzana">
            <option value="Naranja">
            <option value="Mango">
            <option value="Guayaba">   
        </datalist>
        <br><br>

        <hr>

        <h2>Input de Fecha</h2><br>
        <input type="date" id="fecha1" name="fecha1"><br>
        <input type="datetime-local" id="fecha2" name="fecha2"><br>
        <input type="week" id="fecha3" name="fecha3"><br>
        <input type="time" id="fecha4" name="fecha4"><br>
        <input type="month" id="fecha5" name="fecha5"><br><br>

        <hr>

        <h2>Input de boton</h2>
        <input type="reset"><br>
        <input type="submit"><br>
        <input type="button" id="boton1" name="boton1" value="Boton 1" onclick="alert('Bienvenidos Explorers');"><br><br>

        <hr>

        <!-- Formularios -->
        <h2>Ejemplo de Formularios</h2>
        <form action="/accion.js" id="form1" method="post">
            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre" name="nombre"><br><br>
            <input type="submit" value="Submit">
            <input type="reset">
        </form>

        <label for="apellido">Apellido:</label>
        <input type="text" id="apellido" name="apellido" form="form1">
    </body>
    </html>


-----------------------------------------------------------------------------------------------------------------------
