<template>
  <main class="bg-blue-600">
    <moro-header />
    <moro-assest-table />
  </main>
</template>

<script>
import moroHeader from '@/components/moroHeader'
import moroAssestTable from '@/components/moroAsstesTable'

export default {
  name: 'App',
  components: {
    moroHeader,
    moroAssestTable
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
