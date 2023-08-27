<script setup lang="ts">

</script>

<template>
  <div class="login-container">
    <div class="login-box">
      <h2>Login</h2>
      <form @submit.prevent="login">
        <div class="input-group">
          <label for="username">Username</label>
          <input type="text" id="username" v-model="username"/>
        </div>
        <div class="input-group">
          <label for="password">Password</label>
          <input type="password" id="password" v-model="password"/>
        </div>
        <button type="submit">Login</button>
      </form>
    </div>
  </div>
</template>

<style scoped>

</style>
