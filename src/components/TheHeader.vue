<template>
  <header class="header">
    <img class="header__img" src="/" alt="Logo" />
    <nav class="header__menu">
      <ul>
        <li><router-link to="/">Home</router-link></li>

        <li><a href="#" v-scroll-to="'#aboutAnchor'">About</a></li>
        <li><a href="#" v-scroll-to="'#skillsAnchor'">Skills</a></li>
        <li><a href="#portfolioAnchor">Portfolio</a></li>
      </ul>
    </nav>
    <router-view />
  </header>
</template>
<script>
export default {
  name: "TheHeader",
};
</script>
