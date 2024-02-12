<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <RespiratoryComp msg="Welcome to my Respiratory Application"/>
  </div>
</template>

<script>
// @ is an alias to /src
import RespiratoryComp from '@/components/RespiratoryComp.vue'

export default {
  name: 'HomeView',
  components: {
    RespiratoryComp
  }
}
</script>
