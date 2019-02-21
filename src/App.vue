<template>
  <div id="app">
      <div class="row">
        <div class="col-md-2"></div>
        <div class="col-md-8 freshmans-body-repeat">
          <freshmans-navbar></freshmans-navbar>
          <img class="freshmans-logo" src="./assets/images/logo_2.png">
        </div>
        <div class="col-md-2"></div>
      </div> 

      <div class="row">
        <div class="col-md-2">
          <!-- <img class="img-fluid" src="./assets/images/predio_esquerda_novo.png"> -->
        </div>

        <div class="col-md-8 freshmans-body-repeat">
          <freshmans-press></freshmans-press>
        </div>
        <div class="col-md-2">
          <!-- <img class="img-fluid" src="./assets/images/predio_direita_novo.png"> -->
        </div>

        <div class="col-md-2"></div>
        <div class="col-md-8 freshmans-body-repeat">
          <freshmans-contact></freshmans-contact>
        </div>
        <div class="col-md-2"></div>

        <div class="col-md-2"></div>
        <div class="col-md-8 freshmans-footer">
          <img class="img-fluid" src="./assets/images/corpo2.png">
        </div>
        <div class="col-md-2"></div>
      </div> 
    </div>
</template>

<script>
import Header from './components/Header.vue'
import Press from './components/Press.vue'
import Contact from './components/Contact.vue'
import NewNavbar from './components/NewNavbar.vue'
export default {
  components: {
    'freshmans-navbar': NewNavbar,
    'freshmans-header': Header,
    'freshmans-press': Press,
    'freshmans-contact': Contact,
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

.freshmans-footer {
  background: url("./assets/images/corpo2.png") no-repeat;
  padding: 0;
}

.freshmans-logo {
  margin: 1rem 12.5%;
  max-width: 75%;

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
