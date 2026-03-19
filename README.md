


<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Tabla de Animales</title>

<style>
body {
    font-family: Arial, sans-serif;
    background: linear-gradient(to right, #74ebd5, #ACB6E5);
    padding: 20px;
}

table {
    width: 80%;
    margin: auto;
    border-collapse: collapse;
    background-color: white;
    border-radius: 12px;
    overflow: hidden;
    box-shadow: 0px 8px 20px rgba(0,0,0,0.2);
}

th {
    background: #2c3e50;
    color: white;
    padding: 15px;
    font-size: 18px;
}

td {
    padding: 12px;
    text-align: center;
    border-bottom: 1px solid #ddd;
}

tr:nth-child(even) {
    background-color: #f2f2f2;
}

tr:hover {
    background-color: #dff9fb;
    transform: scale(1.01);
    transition: 0.3s;
}

img {
    width: 120px;
    height: 100px;
    object-fit: cover;
    border-radius: 10px;
    border: 3px solid #3498db;
}

b {
    color: #2c3e50;
    font-size: 16px;
}
</style>

</head>

<body>

<table>

<tr>
<th>Imagen</th>
<th>Animal</th>
<th>Descripción</th>
</tr>

<tr>
<td><img src="https://upload.wikimedia.org/wikipedia/commons/6/6e/Golde33443.jpg"></td>
<td><b>Perro</b></td>
<td>Animal doméstico conocido por su lealtad.</td>
</tr>

<tr>
<td><img src="https://upload.wikimedia.org/wikipedia/commons/3/3a/Cat03.jpg"></td>
<td><b>Gato</b></td>
<td>Felino doméstico ágil e independiente.</td>
</tr>

<tr>
<td><img src="https://upload.wikimedia.org/wikipedia/commons/7/73/Lion_waiting_in_Namibia.jpg"></td>
<td><b>León</b></td>
<td>Gran felino africano conocido como rey de la selva.</td>
</tr>

<tr>
<td><img src="https://upload.wikimedia.org/wikipedia/commons/3/37/African_Bush_Elephant.jpg"></td>
<td><b>Elefante</b></td>
<td>El mamífero terrestre más grande.</td>
</tr>

<tr>
<td><img src="https://upload.wikimedia.org/wikipedia/commons/0/0d/Emperor_penguin_manchot_empereur.jpg"></td>
<td><b>Pingüino</b></td>
<td>Ave que no vuela y nada muy bien.</td>
</tr>

<tr>
<td><img src="https://upload.wikimedia.org/wikipedia/commons/5/56/Tiger.50.jpg"></td>
<td><b>Tigre</b></td>
<td>Felino salvaje con rayas negras.</td>
</tr>

<tr>
<td><img src="https://upload.wikimedia.org/wikipedia/commons/9/9f/Giraffe_standing.jpg"></td>
<td><b>Jirafa</b></td>
<td>Animal africano de cuello largo.</td>
</tr>

<tr>
<td><img src="https://upload.wikimedia.org/wikipedia/commons/6/63/Plains_Zebra_Equus_quagga.jpg"></td>
<td><b>Cebra</b></td>
<td>Animal con rayas negras y blancas.</td>
</tr>

<tr>
<td><img src="https://upload.wikimedia.org/wikipedia/commons/0/0f/Grosser_Panda.JPG"></td>
<td><b>Panda</b></td>
<td>Oso que come principalmente bambú.</td>
</tr>

<tr>
<td><img src="https://upload.wikimedia.org/wikipedia/commons/4/49/Koala_climbing_tree.jpg"></td>
<td><b>Koala</b></td>
<td>Mamífero australiano que vive en árboles.</td>
</tr>

</table>

</body>
</html>
