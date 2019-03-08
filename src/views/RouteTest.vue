<template>
  <div class="about">
    <h1>Route Test</h1>
    <p>{{text}}</p>
  </div>
</template>

<script>
import { mapState } from 'vuex';

export default {
  name: 'RouteTest',
  computed: {
    ...mapState([
      'text'
    ])
  }
}
</script>