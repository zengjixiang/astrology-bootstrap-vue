<template>
  <main>
    <div>

      <!-- tailwind.min.css -->
      <!-- <link href="https://unpkg.com/tailwindcss@^2/dist/tailwind.min.css" rel="stylesheet"> -->

      <!-- bootstrap.min.css -->
      <!-- <link href="https://unpkg.com/bootstrap/dist/css/bootstrap.min.css" rel="stylesheet"> -->

      <!-- JavaScript Bundle with Popper -->

      <link
        href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.1/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-/bQdsTh/da6pkI1MST/rWKFNjaCP5gBSY4sEBT38Q/9RBh9AH40zEOg7Hlq2THRZ"
        crossorigin="anonymous"
      />

      <link
        href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.1/dist/css/bootstrap.min.css"
        rel="stylesheet"
      />

      <NuxtLink to="/" class="justify">系統首頁 | </NuxtLink>

      <NuxtLink to="/login" class="justify">系統登入 | </NuxtLink>

      <NuxtLink to="/planet" class="justify">行星資訊 | </NuxtLink>

      <NuxtLink to="/asteroid" class="justify">小行星資訊 | </NuxtLink>

      <NuxtLink to="/about" class="justify">關於作者 | </NuxtLink>
    </div>
  </main>
</template>

<script>
import Vue from "vue";
import { BootstrapVue, IconsPlugin } from "bootstrap-vue";
import "bootstrap/dist/css/bootstrap.css";
import "bootstrap-vue/dist/bootstrap-vue.css";
import "bootstrap/dist/js/bootstrap.bundle.js"
Vue.use(BootstrapVue);


</script>

<script setup>


</script>
