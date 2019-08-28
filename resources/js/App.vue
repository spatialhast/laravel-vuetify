<template>
  <v-app>
    <v-app-bar app>
      <v-toolbar-title class="headline text-uppercase">
        <span
          to="/"
        >Vuetify</span>&nbsp;
        <span class="font-weight-light">App</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn text to="/">
        <v-icon>help_outline</v-icon>
        <span class="ml-2 mr-2">Home</span>
      </v-btn>
      <v-btn text to="/about">
        <v-icon>help_outline</v-icon>
        <span class="ml-2 mr-2">About</span>
      </v-btn>
    </v-app-bar>

    <v-content>
      Content
    </v-content>
  </v-app>
</template>

<script>
export default {

}
</script>

<style lang="sass">
.sass
  background: map-get($material-light, 'cards')
</style>

<style lang="scss">
.scss {
  background: map-get($material-light, 'cards')
}
</style>
