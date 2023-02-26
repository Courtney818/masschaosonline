<template>
  <v-app>
    <!-- We like our site DARK -->
    <v-main class="bg-black dark:bg-black">
      <router-view />
    </v-main>
  </v-app>
</template>

<script>
export default {
  name: 'App',

  data: () => ({
    //
  }),
};
</script>
