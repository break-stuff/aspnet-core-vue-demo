<template>
  <h1><strong>{{ showGreeting() }}</strong></h1>
</template>

<script>
export default {
  name: 'vue-component',
  props: [
    'title'
  ],
  data () {
    return {
      msg: 'Hello from the Vue component!!!!'
    }
  },
  methods: {
    showGreeting() {
      return `Hello from the Vue Component on the ${this.title} page!!!`;
    }
  }
}
</script>

<style lang="scss">
</style>
