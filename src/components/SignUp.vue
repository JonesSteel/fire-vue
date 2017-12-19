<template>
    <div class="sign-up">
      <h3>¡Registrate!</h3>
      <input type="text" placeholder="Email"/><br>
      <input type="password" placeholder="Password"/><br>
      <button>Registrarse</button>
      <span>o vuelve al <router-link to="/login">Inicio de Sesión.</router-link></span>
    </div>
</template>

<script>
    export default {
      name: 'signUp',
      data: function () {
        return {}
      },
      methods: {}
    }
</script>

<style scoped>
  .sign-up {
    margin-top: 40px;
  }
  input {
    margin: 10px 0;
    width: 20%;
    padding: 15px;
  }
  button {
    margin-top: 10px;
    width: 10%;
    cursor: pointer;
  }
  span {
    display: block;
    margin-top: 20px;
    font-size: 11px;
  }
</style>
