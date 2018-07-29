<template>
  <div class="text-xs-center">
    <v-dialog
      v-model="dialog"
      width="500"
    >
      <v-btn
        slot="activator"
        color="red lighten-2"
        dark
      >
        Click Me
      </v-btn>

      <v-card>
        <img src="@/assets/logo.png" />
      </v-card>
    </v-dialog>
  </div>
</template>


<script>
  export default {
    data () {
      return {
        dialog: false
      }
    }
  }
</script>