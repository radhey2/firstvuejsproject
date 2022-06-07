<template>
 <div id="app">
  <input v-model="checkedNames" type="checkbox" id="john" value="John"/>
  <label for="john"> John</label>
  
  <input v-model="checkedNames" type="checkbox" id="paul" value="Paul"/>
  <label for="paul"> Paul</label>
  
  <input v-model="checkedNames" type="checkbox" id="george" value="George"/>
  <label for="george"> George</label>
  
  <input v-model="checkedNames" type="checkbox" id="ringo" value="Ringo"/>
  <label for="ringo"> Ringo</label>
  <br>
  <span>Checked names: {{ checkedNames }}</span>
</div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
   data() {
    return {
      checkedNames: []
    }
  }
}
</script>
