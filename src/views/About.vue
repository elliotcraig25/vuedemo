<template>
  <div class="about">
    <h1>{{text}}</h1>
  </div>
</template>

<script>
import { mapState } from 'vuex';

export default {
  name: 'About',
  computed: {
    ...mapState([
      'text'
    ])
  }
}
</script>