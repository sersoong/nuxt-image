<template>
  <v-layout
    column
    justify-center
    align-center
  >
    <v-flex
      xs12
      sm8
      md6
    >
      <v-img :src="imgsrc" width="120" height="120"/>
    </v-flex>
  </v-layout>
</template>

<script>
export default {
  data(){
    return {
      imgsrc:'/v.png'
    }
  }
}
</script>
