<template>
  <v-app>
    <v-app-bar app color="primary" dark>
      <div class="d-flex align-center">User Details</div>

      <v-spacer></v-spacer>
    </v-app-bar>

    <v-main>
      <DataTableVue />
    </v-main>
  </v-app>
</template>

<script>
import DataTableVue from './components/DataTable.vue'
export default {
  name: 'App',

  components: {
    DataTableVue,
  }
}
</script>
