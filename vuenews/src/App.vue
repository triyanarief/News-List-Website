<template>
  <div class="container" id="app">
    <SourceSelection></SourceSelection>
    <NewsList></NewsList>
  </div>
</template>

<script>
import Newslist from './components/Newslist'
import SourceSelection from './components/SourceSelection'

export default {
  name: 'app',
  components: {
    Newslist,
    SourceSelection
  },
  data () {
    return {
      source: ""
    }
  }
}
</script>

<style>
#app {

}
</style>
