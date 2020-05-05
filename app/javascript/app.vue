<template>
   <div id="app">
  </div>
</template>

<script>
  export default {
    data() {
      return {
        toDo: {
          csrfToken: document.getElementsByName('csrf-token')[0].content,
          title: '',
          expiredAt: '',
          action: '/to_dos'
        }
      }
    }
  }
</script>

<style scoped>
p {
  font-size: 2em;
  text-align: center;
}
</style>
