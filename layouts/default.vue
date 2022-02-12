<template>
  <v-app>
    <nuxt></nuxt>
  </v-app>
</template>

<script>
export default {
  name: 'DefaultLayout',
  data () {
    return {
      clipped: false,
      drawer: false,
      fixed: false,
      items: [
        {
          icon: 'mdi-apps',
          title: 'Welcome',
          to: '/'
        },
        {
          icon: 'mdi-chart-bubble',
          title: 'Inspire',
          to: '/inspire'
        }
      ],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: 'Vuetify.js'
    }
  }
}
</script>

<style>
    .v-app-bar{
      background-color:#1b1b1b !important;
    }
    .v-application{
        font-family: 'Quicksand', sans-serif;
        font-weight: bold;
    }
    .v-application .primary{
        background-color: #1A56BE !important;
        border-color: #1A56BE !important;
    }
    .v-toolbar__title{
      width: 100%;
      text-align: center;
      text-valign: center;
      color: white;
      font-size: 20px;
      font-weight: bold;
    }
    .text-primary{
      color: white;
    }
    .text-title{
      font-size: 18px;
      font-weight: bold;
      color: white;
    }
    .text-subtitle{
      font-size: 15px;
      font-weight: bold;
      color:black;
    }
    .w-100{
      width: 100%;
    }
    .main-btn{
      font-size: 18px;
      font-weight: bold;
      background-color:black !important;
      color: white !important;
      height: 40px !important;
      
    }
    .sub-btn{
      font-size: 15px;
      font-weight: bold;
      background-color:grey !important;
      color: black !important;
      height: 50px !important;
      
    }
    
</style>
