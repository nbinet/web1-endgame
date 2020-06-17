<template>
  <div class="template background">
    <Template link='/80s' />
    <img id="traproll" src="../img/home/logo.png" />
    <img id="sub" src="../img/home/subtitle.png" />
    <p class="disclaimer">Ce site a été réalisé à des fins pédagogiques dans le cadre du cursus Bachelor de l'école HETIC. Les contenus présentés n'ont pas fait l'objet d'une demande de droit d'utilisation. Ce site ne sera en aucun cas exploité à des fins commerciales et ne sera pas publié</p>
  </div>
</template>

<script>
// @ is an alias to /src
//import Background from "@/components/Background.vue";
import Template from './template.vue'

export default {
  name: 'Home',
  components: {
    Template
  }
}

</script>

<style scoped lang="scss">

.template {
  width: 100%;
  height: 100%;
}

.background {
  background-image: url("../img/home/background.png");
  margin:0;
  padding:0;
  background-size: cover;
}

#traproll {
  display: block;
  margin-left: auto;
  margin-right: auto;
  padding-top: 100px;
}

#sub {
  display: block;
  margin-left: auto;
  margin-right: auto;
}

.disclaimer {
  position: absolute;
  font-size: 10px;
  left:0;
  bottom:0;
  width: 30vw;
  color: white;
  opacity: 0.3;
}

</style>
