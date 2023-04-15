<template>
  <v-app>
    <v-app-bar color="primary" dark app>
      <router-link to="/">
        <v-toolbar-title class="page-title">Formátovač v4.0</v-toolbar-title>
      </router-link>
    </v-app-bar>
    <v-content>
      <router-view></router-view>
    </v-content>
  </v-app>
</template>

<script>
export default {
  name: "App",
  components: {},
  data: () => ({}),
};
</script>

<style scoped>
.page-title {
  color: #fff;
  font-weight: bold;
}
</style>
