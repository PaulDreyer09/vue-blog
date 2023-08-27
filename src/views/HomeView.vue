<template>
  <div class="home">
    <h1>Home</h1>

  </div>
</template>

<script>
import { ref, computed, watch, watchEffect } from 'vue';
// @ is an alias to /src


export default {
  name: 'HomeView',
  setup() {
    const posts = ref([
      {title: 'Welcome to the blog', body: 'Lorem ipsum', id: 1},
      {title: 'Top 5 CSS tips', body: 'Lorem ipsum', id: 2},

    ])

    return {

    }
  }
}
</script>
