<template>
  <v-container class="fill-height d-flex justify-center align-center">
    <v-card
      class="pa-8"
      elevation="12"
      color="blue-grey-lighten-5"
      max-width="500"
      width="100%"
    >
      <v-card-title class="text-center text-h5 font-weight-bold mb-6">
        Iniciar Sesión
      </v-card-title>

      <v-card-text>
        <v-text-field
          class="mb-4"
          prepend-inner-icon="mdi-email"
          hide-details="auto"
          label="Correo electrónico"
          placeholder="ejemplo@correo.com"
          type="email"
          variant="outlined"
          density="comfortable"
        ></v-text-field>

        <v-text-field
          prepend-inner-icon="mdi-lock"
          hide-details="auto"
          label="Contraseña"
          placeholder="Ingresa tu contraseña"
          type="password"
          variant="outlined"
          density="comfortable"
        ></v-text-field>
      </v-card-text>

      <v-card-actions class="mt-6">
        <v-btn
          color="primary"
          rounded="lg"
          size="large"
          block
          elevation="2"
        >
          Iniciar Sesión
        </v-btn>
      </v-card-actions>
    </v-card>
  </v-container>
</template>


<script setup>
  // No es necesario ningún script por ahora
</script>

<style scoped>
/* Opcional: centrar completamente en pantalla si el contenedor lo permite */
html, body {
  height: 100%;
  margin: 0;
}
</style>
