<template>
  <div class="about">
    <h1>{{ platform.description }}</h1>
  </div>
</template>

<script>
import Platform from 'platform';

export default {
  name: 'About',
  data() {
    return {
      platform: Platform,
    };
  },
};
</script>
