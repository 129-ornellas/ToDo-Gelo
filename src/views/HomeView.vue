<template>
  <v-container>
    <v-row class="text-center">
      <v-col cols="12"> </v-col>

      <v-col class="mb-4">
        <img
          src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSq4zAFnEZkb16Cf5VcPx4xZBdIFMKtUsG0YO6OmiwfQdK1DWezB-hbcKeDGGwCLo24HWg&usqp=CAU"
          alt=""
        />
        <h1 class="display-2 font-weight-bold mb-3">ToDo List</h1>

        <p class="subheading font-weight-regular">
          Crie suas tarefas, acompanhe os graficos.
        </p>
        <p>
          <v-btn x-large rounded color="primary" dark :to="{ name: 'login' }">
            Iniciar
          </v-btn>
        </p>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {}
</script>
