<template>
  <header class="header">
    <ul class="nav-items">
      <li>
        <nuxt-link style="text-decoration:none;" to="/">Home</nuxt-link>
      </li>
      <li>
        <nuxt-link style="text-decoration:none;" to="/users">Users</nuxt-link>
      </li>
    </ul>
  </header>
</template>

<style scoped>
  .header{
    width: 100%;
    height: 60px;
    display: flex;
    align-items: center;
    justify-content: center;
    background: #ddd;
  }

  .nav-items{
    list-style: none;
    padding:0;
    margin:0;
    display:flex;
    justify-content:space-around;
    align-items:center;
    width: 80%;
  }
</style>
