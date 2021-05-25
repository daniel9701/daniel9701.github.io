# daniel9701.github.io
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Formulario</title>
  </head>
  <body>   
    <form action="javascript:saluda();">      
      <h1>Formulario</h1>
      <p>        
        <input type="text" id="boleta" required placeholder="Boleta">
		<input type="text" id="nombre" required placeholder="Nombre">
        <input type="text" id="grupo" required placeholder="Grupo">
        <input type="text" id="materia" required placeholder="Materia">
		<input type="date" id="fecha" required placeholder="Fecha">
      </p>
      <p>        
        <button type="submit">Saludar</button>
      </p>
      <footer>Copyright &copy; 2021 Palma Hernandez Daniel.</footer>
    </form>   
    <script>    
      function saluda() {       
        const respuesta = `Saludos a ${boleta.value}, ${nombre.value},${boleta.value},${grupo.value},${materia.value},${fecha.value}.`;
        alert(respuesta);
      }
    </script>
    <footer>
    </footer>
  </body>
</html>
