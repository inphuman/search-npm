<template>
    <v-app-bar
            app
            color="primary"
            dark
    >
        <div class="d-flex align-center">
            <v-img
                    alt="Vuetify Logo"
                    class="shrink mr-2"
                    contain
                    src="https://cdn.vuetifyjs.com/images/logos/vuetify-logo-dark.png"
                    transition="scale-transition"
                    width="40"
            />

            <div class="app-bar__logo">Search NPM</div>
        </div>

        <v-spacer></v-spacer>

<!--        <v-btn-->
<!--                href="https://github.com/vuetifyjs/vuetify/releases/latest"-->
<!--                target="_blank"-->
<!--                text-->
<!--        >-->
<!--            <span class="mr-2">Latest Release</span>-->
<!--            <v-icon>mdi-open-in-new</v-icon>-->
<!--        </v-btn>-->
    </v-app-bar>
</template>

<script>
export default {
    name: "AppBar"
}
</script>

<style lang="scss">
  .app-bar {
    &__logo {
      font-size: large;
      font-weight: bold;
    }
  }
</style>