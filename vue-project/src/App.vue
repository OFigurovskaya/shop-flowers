<script>
import Header from './components/Header.vue';
import Main from './pages/Main.vue';
import Footer from './components/Footer.vue';

export default {
  name: 'App',
  data () {
    return {

    }
  },
  components: {
    Header,
    Main,
    Footer
  }
}
</script>

<template>
  <Header />
  <Main />
  <Footer />
</template>