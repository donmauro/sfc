<template>
  <div id="app">
    <h1 class="ui center aligned header">Tutorial</h1>
    <StaffDirectory />
  </div>
</template>

<script>
import 'semantic-ui-css/semantic.css'
import StaffDirectory from './components/StaffDirectory.vue'

export default {
  name: 'app',
  components: {
    StaffDirectory
  }
}
</script>