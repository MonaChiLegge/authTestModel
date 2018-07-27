<template>
  <div class="login-form">
    <input class="login-input" type="text" name="e-mail" placeholder="Your e-mail" autofocus>
    <input class="login-input" type="password" name="pwd" placeholder="Your password">
    <input class="login-submit" type="button" name="login" value="Submit">
  </div>
</template>

<script>
export default {
  name: "LoginForm"
};
</script>

<style scoped>
.login-form {
  width: 100%;
  background-color: white;
  padding: 20px;
}

.login-input {
  width: calc(100% - 50px);
  height: 30px;
  padding: 5px;
  background-color: #edeae6;
  border: 2px solid #edeae6;
  margin-top: 20px;
  box-shadow: 0px 5px 10px gray;
}

.login-input:focus {
  background-color: white;
  border-color: white;
  box-shadow: 0px 5px 20px black;
  // box-shadow:
}

.login-submit {
  width: calc(100% - 35px);
  margin-top: 20px;
  height: 50px;
  background-color: #dbd0ba;
  border: 2px solid black;
}

.login-submit:active {
  background-color: #c6b38b;
  border: 2px solid black;
  box-shadow: 0px 5px 10px gray;
}
</style>
