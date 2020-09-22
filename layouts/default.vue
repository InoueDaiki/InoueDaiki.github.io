<template>
  <v-app>
    <v-app-bar app>
      <v-toolbar-title>
        白柳 大樹
        <small>のプロフィール</small>
      </v-toolbar-title>
      <v-spacer />
      <v-btn
        icon
        href="https://www.linkedin.com/in/ShirayanagiDaiki"
        target="_brank"
      >
        <v-icon>mdi-linkedin</v-icon>
      </v-btn>
      <v-btn icon href="https://github.com/InoueDaiki" target="_brank">
        <v-icon>mdi-github</v-icon>
      </v-btn>
    </v-app-bar>
    <v-main>
      <nuxt />
    </v-main>
  </v-app>
</template>

<script>
export default {}
</script>
