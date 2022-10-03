<template>
  <div class="home">
    <principalPage/>
  </div>
</template>

<script>
// @ is an alias to /src
import principalPage from '@/components/principal-page.vue'

export default {
  name: 'HomeView',
  components: {
    principalPage
  }
}
</script>
