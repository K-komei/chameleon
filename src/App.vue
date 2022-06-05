<template>
  <v-app>
    <v-main>

      <from-row>
      <DeveloperArea></DeveloperArea>
      <DeveloperArea></DeveloperArea>
      <DeveloperArea></DeveloperArea>

      </from-row>
      <DeveloperArea></DeveloperArea>
    </v-main>
  </v-app>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import DeveloperArea from './components/DeveloperArea.vue'

export default {
  name: 'App',

  components: {
  //  HelloWorld,
    DeveloperArea
},

  data: () => ({
    //
  }),
}
</script>
