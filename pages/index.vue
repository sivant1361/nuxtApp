<template>
  <div>
    <Header />
    <h3>
      Click Here !
      <nuxt-link to="users" style="text-decoration:none;">Users</nuxt-link>
    </h3>
  </div>
</template>

<script>
  import Header from '~/components/Header.vue'
  export default {
    components: {Header}
  }
</script>
