<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <FormCandidat/>
  </div>
</template>

<script>
// @ is an alias to /src
import FormCandidat from '@/components/FormCandidat.vue'

export default {
  name: 'home',
  components: {
    FormCandidat
  }
}
</script>
