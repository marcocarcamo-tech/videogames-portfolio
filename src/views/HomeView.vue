<template>
  <div class="home">
    <header class="header">
      <a href="/" style="width: 10%; height: 80%"
        ><img class="header__img" src="../assets/img/logotipo.png" alt="Logo"
      /></a>
      <nav class="header__menu">
        <ul>
          <li><a href="#" v-scroll-to="'#aboutAnchor'">Acerca</a></li>
          <li><a href="#" v-scroll-to="'#skillsAnchor'">Skills</a></li>
          <li><a href="#" v-scroll-to="'#portfolioAnchor'">Portafolio</a></li>
          <li><a href="#" v-scroll-to="'#contactAnchor'">Contacto</a></li>
        </ul>
      </nav>
    </header>

    <a id="aboutAnchor"></a>
    <AboutSection />
    <a id="skillsAnchor"></a>
    <SkillsSection />
    <a id="portfolioAnchor"></a>
    <PortfolioSection />
    <a id="contactAnchor"></a>
    <ContactSection />
    <TheFooter />
  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from "@/components/HelloWorld.vue";
import AboutSection from "../components/AboutSection.vue";
import SkillsSection from "../components/SkillsSection.vue";
import PortfolioSection from "../components/PortfolioSection.vue";
import ContactSection from "../components/ContactSection.vue";
import TheFooter from "../components/TheFooter.vue";
export default {
  name: "HomeView",
  components: {
    AboutSection,
    SkillsSection,
    PortfolioSection,
    ContactSection,
    TheFooter,
  },
};
</script>
