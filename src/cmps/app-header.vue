<template>
  <header>
    <img class="logo" src="../assets/images/logo.svg" alt="">
    <nav class="main-nav">
      <router-link to="/">Features</router-link>
      <router-link to="/car">Team</router-link>
      <router-link to="/login">Sign in</router-link>
    </nav>
  </header>
</template>
<script>
export default {
  computed: {
    loggedInUser() {
      return this.$store.getters.loggedinUser
    },
  }
}
</script>