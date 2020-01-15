<template>
  <v-content>
      <section>
        <v-parallax src="assets/hero.jpeg" height="600">
          <v-layout
            column
            align-center
            justify-center
            class="white--text"
          >
            <img src="assets/logo_banbondoi.png" alt="logo_banbondoi" height="200">
            <h1 class="white--text mb-2 display-3 text-center">บ้านบนดอย</h1>
            <div class="subheading mb-4 text-center">Powered by Vuetify</div>
            <v-btn
              class="mt-12"
              color="blue lighten-2"
              dark
              large
              href="/pre-made-themes"
            >
              Get Started Banbondoi
            </v-btn>
          </v-layout>
        </v-parallax>
      </section>
    </v-content>
</template>

<script>
export default {
  name: 'home',
};
</script>
