<template>
  <header>
    <nav class="navbar has-background-dark is-dark"
    role="navigation"
    aria-label="main navigation">
    <HeaderBarLinks></HeaderBarLinks>
  </nav>
  </header>
</template>

<script>
import { HeaderBarLinks } from './header-bar-links.vue';

export default {
  name: 'HeaderBar',
  components: { HeaderBarLinks },
};
</script>
