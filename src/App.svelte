<script>
  import FotoPiscina from './lib/fotoPiscina.svelte';
  import Formulario from './lib/formulario.svelte';
</script>

<main>
  <div>
    <FotoPiscina />
    <Formulario />
  </div>
</main>

<style>
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  main {
    display: flex;
    flex-direction: column; 
    justify-content: center;
    align-items: center;
    width: 100%;
    height: 100%; 
    background-color: #006080; 
  }

  div {
    display: flex;
    flex-direction: column; 
    justify-content: center;
    align-items: center;
    width: 100%;
    height: auto; 
  }
</style>
