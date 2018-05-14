<template>
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <router-link :to="{ name: 'home'}"  class="navbar-brand" >Cars App</router-link>
 
  <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav">
      <li class="nav-item active">
         <router-link :to="{ name: 'cars' }" class="nav-link">Cars </router-link>
      </li>
      <li class="nav-item">
        <router-link :to="{ name: 'add' }" class="nav-link">Add Car</router-link>
      </li>
      
    </ul>
  </div>
</nav>
</template>
<script>
</script>