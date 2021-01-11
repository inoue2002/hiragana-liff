<template>
  <v-app>
    <v-app-bar
      fixed
      app
    >
    ルビ振りアプリ
    <v-spacer />
    <v-btn icon to='information'>
      <v-icon>
        mdi-information-outline
      </v-icon>

    </v-btn>
    </v-app-bar>

    <v-main>
      <v-container>
        <nuxt />
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
export default {
  data () {
    return {
    }
  }
}
</script>
