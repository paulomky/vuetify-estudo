<template>
  <v-app>
    <v-card width="500" class="mx-auto mt-5">
      <v-card-title><h1 class="display-1">Login</h1></v-card-title>
      <v-card-text>
        <v-form>
          <v-text-field
            label="Username"
            prepend-icon="mdi-account-circle"
          ></v-text-field>
          <v-text-field
            label="password"
            prepend-icon="mdi-lock"
            append-icon="mdi-eye"
          >
          </v-text-field>
        </v-form>
      </v-card-text>
      <v-card-actions>
        <v-btn color="success">Register</v-btn>
        <v-spacer></v-spacer>
        <v-btn color="info">Login</v-btn>
      </v-card-actions>
    </v-card>
  </v-app>
</template>

<script>
export default {
  name: "App",

  components: {},

  data: () => ({
    //
  }),
};
</script>
