<template>
  <div id="app">
    <HeroHeader />
    <MainContent />
    <Footer />
  </div>
</template>

<script>
import HeroHeader from './components/HeroHeader';
import MainContent from './components/MainContent';
import Footer from './components/Footer';

export default {
  name: 'App',
  components: {
    HeroHeader,
    MainContent,
    Footer,
  }
}
</script>

<style>
html, body{
  margin: 0;
  padding: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
</style>
