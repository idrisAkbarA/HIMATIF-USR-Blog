<template>
  <v-layout
    column
    justify-center
    align-center
  >
    <v-container fluid fill-height>
      <v-card>
        <v-card-title>
          Hey! Blog Himatif Lagi dibuat lo!!!
        </v-card-title>
        <v-card-text>
          Semangat!!!
        </v-card-text>
      </v-card>
    </v-container>
  </v-layout>
</template>

<script>
import Logo from '~/components/Logo.vue'
import VuetifyLogo from '~/components/VuetifyLogo.vue'

export default {
  components: {
    Logo,
    VuetifyLogo
  }
}
</script>
