<template>
  <div class="sticky-top">
    <nav
      class="navbar shadow bg-white rounded justify-content-between flex-nowrap flex-row"
      style="margin-bottom: 2rem"
    >
      <div class="container">
        <router-link to="/" class="navbar-brand float-left"
          >Vuex Course</router-link
        >
        <ul class="nav navbar-nav d-flex flex-row bd-highlight">
          <li class="nav-item me-5">
            <router-link to="/heroes" exact class="nav-link">
              Heroes</router-link
            >
          </li>
          <li class="nav-item">
            <router-link to="/anti-heroes" exact class="nav-link">
              Anti-Heroes</router-link
            >
          </li>
        </ul>
      </div>
    </nav>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "Navbar",
});
</script>

<style scoped></style>
