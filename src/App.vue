<template>
  <div id="app">
    <h1 class="bg-yellow-600 
    text-center
    text-3xl
    text-white
    font-bold
    my-10
    p-10">
    Hello World!</h1>
    <first />
  </div>
</template>

<script>
import first from './components/FirstComponent.vue'
export default {
 name:"App",
 components: {
    first
  },
}
</script>

