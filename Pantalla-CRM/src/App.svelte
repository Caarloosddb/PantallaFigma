<script>
  import Registro from "./lib/Registro.svelte";
  import Flecha from "./lib/Flecha.svelte";
</script>

<main>
  <div class="flecha">  <Flecha /></div>

  <img src="src/assets/NombreBlanco.png" alt="">
  <h1>Registrarse</h1>
  <Registro />
</main>

<style>
  main {
      font-family: Arial, sans-serif;
      background-color: #FF3B30;
      height: 100%;
      width: 100%;
      display: flex;
      flex-direction: column;
      align-items: center;
  }
  h1{
    color: white;
  }
  img {
      width: 90%;
      height: auto;
  }
  .flecha{
    display: flex;
    align-items: center;
    justify-content: flex-start;
    width: 90%;
    padding: 10px;
  }
</style>