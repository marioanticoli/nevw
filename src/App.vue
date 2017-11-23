<template>
  <div id="app">
  </div>
</template>

<script>
import {ipcRenderer} from 'electron'
import Datastore from 'nedb'

export default {
  name: 'app',
  components: {
    Profile,
    Page
  },
  data: function () {
    return {
    }
  },
  computed: {
  },
  created: function () {
    ipcRenderer.on('message-name', (event, res) => {
    })
  },
  methods: {
  }
}
</script>

<style>
</style>
