<template>
  <header class="header">
    <nav class="nav">
      <ul class="nav-links">
        <li class="link">
          <router-link to="/">Login</router-link>
        </li>
      </ul>
    </nav>
    <slot></slot>
  </header>
</template>

<script>
export default {
};
</script>

<style scoped>
  .header {
    width: 100%;
    height: 70px;
    background-color: #333333;
    box-sizing: border-box;
    padding: .5em;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .nav {
    width: 600px;
  }

  .nav-links {
    width: 100%;
    display: flex;
    justify-content: flex-start;
  }

  .link {
    list-style: none;
    padding: 0 2em;
  }

  .link a {
    color: #fff;
    text-decoration: none;
  }
</style>
