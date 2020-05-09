<template>
  <v-app>
    <v-toolbar fixed>
      <v-toolbar-title v-text="title" />
    </v-toolbar>
    <v-content>
      <nuxt />
    </v-content>
    <v-footer center>
      <v-layout justify-center>
        <span>&copy; This project is referenced from https://tech.fusic.co.jp/posts/2019-08-23-rails-nuxt-graphql-todoapp/</span>
      </v-layout>
    </v-footer>
  </v-app>
</template>

<script >
export default {
  data() {
    return {
      title: "Tasks"
    };
  }
};
</script>
