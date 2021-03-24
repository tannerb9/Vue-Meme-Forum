<template>
  <v-app>
    <v-app-bar app color="teal darken-1" dark>
      <h1>Vue Memes</h1>
      <v-spacer></v-spacer>
      <router-link class="tab" to="/create">Create</router-link>
      <router-link class="tab" to="/feed">Memes</router-link>
    </v-app-bar>

    <v-main>
      <router-view></router-view>
    </v-main>
  </v-app>
</template>

<script>
export default {};
</script>

<style scoped>
.tab {
  text-decoration: none;
  color: white;
  padding: 10px;
}

.router-link-active {
  color: rgba(101, 253, 215, 0.726);
}
</style>
