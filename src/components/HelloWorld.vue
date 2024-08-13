<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="tela-login">
    <h1>Login</h1>
    <input type="text" id="nome" placeholder="Nome" />
    <br /><br />
    <input type="password" id="senha" placeholder="Senha" />
    <br /><br />
    <button type="button" id="enviarBtn">Enviar</button>
  </div>
</template>

<style scoped>
body {
  font-family: Arial, Helvetica, sans-serif;
  background-color: linear-gradient(45deg, cyan, black);
}

.tela-login {
  background-color: rgba(0, 0, 0, 0.8);
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  padding: 80px;
  border-radius: 15px;
  color: white;
}

input {
  padding: 15px;
  border: none;
  outline: none;
  font-size: 15px;
  border-radius: 10px;
}

button {
  background-color: dodgerblue;
  border: none;
  padding: 15px;
  width: 100%;
  border-radius: 10px;
  color: white;
  font-size: 15px;
}

button:hover {
  background-color: rgba(0, 0, 0, 0.7);
  cursor: pointer;
}
</style>
