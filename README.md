<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Tabla de Animales</title>
<style>
    body{
        font-family: Arial, sans-serif;
        background: linear-gradient(135deg, #a8edea, #fed6e3);
        text-align: center;
    }

    h1{
        color: #333;
        margin-top: 20px;
    }

    table{
        margin: auto;
        border-collapse: collapse;
        width: 80%;
        background: white;
        border-radius: 10px;
        overflow: hidden;
        box-shadow: 0px 5px 15px rgba(0,0,0,0.2);
    }

    th{
        background: #4CAF50;
        color: white;
        padding: 12px;
        font-size: 18px;
    }

    td{
        padding: 12px;
        border-bottom: 1px solid #ddd;
    }

    tr:nth-child(even){
        background-color: #f2f2f2;
    }

    tr:hover{
        background-color: #ffeaa7;
        transition: 0.3s;
    }

    img{
        width: 120px;
        height: 90px;
        border-radius: 10px;
        border: 3px solid #4CAF50;
    }
</style>
</head>

<body>

<h1>🐾 Tabla de Animales</h1>

<table>
<tr>
<th>Animal</th>
<th>Imagen</th>
<th>Descripción</th>
</tr>

<tr>
<td>León</td>
<td><img src="https://upload.wikimedia.org/wikipedia/commons/7/73/Lion_waiting_in_Namibia.jpg"></td>
<td>El león es conocido como el rey de la selva y es un gran depredador.</td>
</tr>

<tr>
<td>Elefante</td>
<td><img src="https://upload.wikimedia.org/wikipedia/commons/3/37/African_Bush_Elephant.jpg"></td>
<td>El elefante es el animal terrestre más grande del mundo.</td>
</tr>

<tr>
<td>Delfín</td>
<td><img src="https://upload.wikimedia.org/wikipedia/commons/0/0c/Dolphin1.jpg"></td>
<td>El delfín es un mamífero marino muy inteligente y sociable.</td>
</tr>

<tr>
<td>Águila</td>
<td><img src="https://upload.wikimedia.org/wikipedia/commons/e/e7/Golden_Eagle_in_flight.jpg"></td>
<td>El águila es un ave rapaz famosa por su gran vista y vuelo.</td>
</tr>

<tr>
<td>Panda</td>
<td><img src="https://upload.wikimedia.org/wikipedia/commons/0/0f/Grosser_Panda.JPG"></td>
<td>El panda es un oso que vive en China y se alimenta principalmente de bambú.</td>
</tr>

</table>

</body>
</html>
