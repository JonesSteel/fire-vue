<template>
    <div class="login">
      <h3>¡Inicia Sesión!</h3>
      <input type="text" placeholder="Email"/><br>
      <input type="password" placeholder="Password"/><br>
      <button>Conectate</button>
      <p>¿Aun no tienes una cuenta? ¡Puedes <router-link to="/sign-up">crear alguna!</router-link></p>
    </div>
</template>

<script>
    export default {
      name: 'login',
      data: function () {
        return {}
      },
      methods: {}
    }
</script>

<style scoped>
  .login {
    margin-top: 40px;
  }
  input {
    margin: 10px 0;
    width: 20%;
    padding: 15px;
  }
  button {
    margin-top: 20px;
    width: 10%;
    cursor: pointer;
  }
  p {
    margin-top: 40px;
    font-size: 13px;
  }

  p a {
    text-decoration: underline;
    cursor: pointer;
  }
</style>
