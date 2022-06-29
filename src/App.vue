<template>
  <nav>
    <router-link to="/" class="profile">
      <img src="./assets/frz.png" alt="">
      <p>FRZ</p>
    </router-link>
    <div class="navigation">
      <router-link to="/">Home</router-link>
      <router-link to="/">Server</router-link>
      <router-link to="/">VIP</router-link>
      <router-link to="/about">About</router-link>
    </div>
    <router-link to="/">Sign Up</router-link>
  </nav>
  <router-view/>
</template>

<script>

// style css
import ('./style/app.scss')

</script>