<template>
  <TheHeroHeader />
  <TheAbout />
  <TheProjects />
  <TheContact />
</template>

<script>
import TheHeroHeader from './components/TheHeroHeader';
import TheAbout from './components/TheAbout';
import TheProjects from './components/TheProjects';
import TheContact from './components/TheContact';

export default {
  name: "App",
  components: {
    TheHeroHeader,
    TheAbout,
    TheProjects,
    TheContact
  },
};
</script>

<style lang="scss">
  * {
    //@import url('https://fonts.googleapis.com/css2?family=Lato:ital,wght@0,100;0,300;0,400;0,700;0,900;1,100;1,300;1,400;1,700;1,900&display=swap');
    //@import url('https://fonts.googleapis.com/css2?family=PT+Sans:ital,wght@0,400;0,700;1,400;1,700&display=swap');
    @import url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300;0,400;0,600;0,700;0,800;1,300;1,400;1,600;1,700;1,800&display=swap');

  }
  
  body {
    margin: 0;
    padding: 0;
  }

  #app {
    margin: 0;
    padding: 0;

    font-family: "Open Sans", sans-serif;
    color: #fff;
  }
</style>
