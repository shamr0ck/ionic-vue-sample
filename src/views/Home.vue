<template>
  <div class="ion-page">
    <ion-header>
      <ion-toolbar>
        <ion-title>About Page</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content class="ion-padding">
      <h1>Welcome To @ionic/vue</h1>
      <img alt="Vue logo" src="../assets/logo.png">
      <ion-button @click="onClick()">Go to About Page</ion-button>
    </ion-content>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  methods:{
    onClick (){
      this.$router.push('about')
    }
  }
  // components: {
    // HelloWorld
  // }
}
</script>
