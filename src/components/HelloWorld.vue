<template>
  <div class="hello">
    
 

  </div>
</template>



<script lang="ts">
import Vue from 'vue';



export default Vue.extend({
  name: 'HelloWorld',
  props: {
    msg: String,
  }, 
  data() {
      return {
        toto: "az" as string
      }
  }
});
</script>

