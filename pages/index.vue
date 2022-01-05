<template>
  <v-app>
    <v-navigation-drawer v-model="drawer" app>
      <!--  -->
    </v-navigation-drawer>

    <v-app-bar app>
      <v-app-bar-nav-icon @click="drawer = !drawer"></v-app-bar-nav-icon>

      <v-toolbar-title>Application Deployment</v-toolbar-title>
    </v-app-bar>

    <v-main>
      <v-container fluid>
        <h1>Bonjour !</h1>
        <p>Test</p>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Officiis,
          inventore ea, nemo provident officia libero atque magni deleniti
          illum, nisi sit totam eaque dolorum. Quod magni modi tempora rerum
          quidem!
        </p>
        <p>Un autre test après push</p>
        <br />
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Atque hic
          optio esse quidem accusamus aut repellat officia suscipit tempora, eos
          ipsa numquam culpa explicabo possimus qui animi repellendus eum autem.
        </p>
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
export default {
  data: () => ({ drawer: null }),
}
</script>