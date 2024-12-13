<script></script>

<div class="formulario">
  <div class="campo">
    <input type="text" id="usuario" name="usuario" placeholder="Usuario">
  </div>
  <div class="campo">
    <input type="password" id="contrasena" name="contrasena" placeholder="Contraseña">
  </div>
  <div class="campo">
    <div class="spacer"></div>
    <button>Iniciar sesión</button>
  </div>
</div>

<style>
  .formulario {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding: 20px;
    border-radius: 10px;
    width: 90%; 
    max-width: 400px; 
  }

  .campo {
    display: flex;
    align-items: center;
    margin: 10px 0;
    width: 100%;
  }


  input {
    padding: 10px;
    flex-grow: 1;
    border: 1px solid #ccc;
    border-radius: 5px;
    font-size: 16px;
  }

  button {
    padding: 10px 15px;
    border: none;
    border-radius: 5px;
    background-color: #00ACE6;
    color: white;
    cursor: pointer;
    font-size: 16px;
    width: 100%;
  }
</style>
