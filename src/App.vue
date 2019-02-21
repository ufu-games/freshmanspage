<template>
  <div id="app">
        <freshmans-navbar></freshmans-navbar>
        <freshmans-logo></freshmans-logo>
        <freshmans-press></freshmans-press>
        <freshmans-contact></freshmans-contact>
        <freshmans-footer></freshmans-footer>
      </div> 
</template>

<script>
import NewNavbar from './components/NewNavbar.vue'
import Logo from './components/Logo.vue'
import Press from './components/Press.vue'
import Contact from './components/Contact.vue'
import Footer from './components/Footer.vue'
export default {
  components: {
    'freshmans-navbar': NewNavbar,
    'freshmans-logo': Logo,
    'freshmans-press': Press,
    'freshmans-contact': Contact,
    'freshmans-footer': Footer,
  }
}
</script>

<style>

.freshmans-body-repeat {
  background: url("./assets/images/corpo1.png") repeat-y;
  background-size: cover;
  margin: 0;
  padding: 1rem 3rem;
}

.col-md-2 {
  margin: 0;
  padding: 0;
}

#app {
  /* background: url("./assets/images/nuvem_nova.png") repeat; */
}

.row {
  margin: 0;
}

html, body {
  background-color: #0ca4a0;
}
html, body, #app, section {
    height: 100%;
    margin: 0 auto;
}

.horizontalAlignment {
    text-align: center;
}

.verticalAlignment {
    display: flex;
    align-items: center;
}
</style>
