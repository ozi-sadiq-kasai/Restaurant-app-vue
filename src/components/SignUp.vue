<template>
  <img class="logo" src="../assets/logo.png" alt="">
  <h1>Sign Up</h1>
  <div class="register">
    <input type="text" placeholder="Enter Name">
    <input type="email" placeholder="Enter Email">
    <input type="password" placeholder="Enter Password">
    <button>Sign Up</button>
  </div>
</template>
<script>
  export default {
    name: 'SignUp'
  }
</script>

<style>
  .logo{
    width: 100px;
  }
  .register input{
    border: 1px solid orange;
    width: 400px;
    height: 40px;
    display: block;
    margin-left: 27rem;
    margin-top: 20px;
    padding-left: 20px;
  }
  .register button{
    margin-top: 30px;
    padding: 10px 50px;
    color: orange;
    background: black;
    border: none;
  }
</style>