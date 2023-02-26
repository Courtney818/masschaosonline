<template>
  <nav>
    <ul>
      <li>
        <router-link to="/">Home</router-link>
      </li>
      <li>
        <router-link to="/about">About</router-link>
      </li>
    </ul>
  </nav>
</template>

<script>
export default {
  name: 'MainNav',
  data: () => ({}),
  methods: {
    //
  },
};
</script>

<style lang="scss" scoped></style>
