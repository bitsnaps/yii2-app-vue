<template>
  <div>
    <div class="jumbotron">
      <img src="img/vue.png" width="15%" /> +
      <img src="img/yii.png" width="15%" />
      <p class="lead">
        You have successfully created your Yii-powered application.
      </p>
      <button-component />
    </div>
    <vue-particles
      color="#dedede"
      :particleOpacity="0.7"
      :particlesNumber="80"
      shapeType="circle"
      :particleSize="4"
      linesColor="#dedede"
      :linesWidth="1"
      :lineLinked="true"
      :lineOpacity="0.4"
      :linesDistance="150"
      :moveSpeed="3"
      :hoverEffect="true"
      hoverMode="grab"
      :clickEffect="true"
      clickMode="push"
    >
    </vue-particles>
  </div>
</template>
<script>
import Vue from 'vue'
import ButtonComponent from './ButtonComponent.vue'

export default {
    components:{
        ButtonComponent
    }
};
</script>

<style>
.jumbotron {
  position: absolute;
  left: 0;
}
</style>
