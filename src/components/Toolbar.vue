<template>
  <v-toolbar dense color="#6A1B9A" dark>
    <v-app-bar-nav-icon></v-app-bar-nav-icon>

    <v-toolbar-title>Title</v-toolbar-title>

    <v-spacer></v-spacer>

    <v-btn icon>
      <v-icon>mdi-magnify</v-icon>
    </v-btn>

    <v-btn icon>
      <v-icon>mdi-heart</v-icon>
    </v-btn>

    <v-btn icon>
      <v-icon>mdi-dots-vertical</v-icon>
    </v-btn>
  </v-toolbar>
</template>



<script>
export default {
  name: "Toolbar"
};
</script>

<style lang="scss" scoped>
// v-toolbar {
//   background-color: #8e24aa;
// }
</style>