<template>
  <nav class="navbar navbar-expand navbar-light bg-light">
  <a class="navbar-brand" href="#">Boolpress</a>


    <ul class="navbar-nav mr-auto">
      <li class="nav-item">
        <router-link class="nav-link" :to="{name: 'home'}">Home</router-link>
      </li>

      <li class="nav-item">
        <router-link class="nav-link" :to="{name: 'about'}">Chi Siamo</router-link>
      </li>
      
      <li class="nav-item">
        <router-link class="nav-link" :to="{name: 'contact'}">Contatti</router-link>
      </li>

      <li class="nav-item">
        <router-link class="nav-link" :to="{name: 'posts'}">Post</router-link>
      </li>
    </ul>
    

</nav>
</template>

<script>
export default {
    name: 'Header'
}
</script>

<style>

</style>