<template>
  <div>
    <h1>Reverse - Rerseve</h1>
    <input type="text" name="wordInput" id="wordInput" placeholder="Input the word." v-model="textWord">   
    <br /><br /> 
    <button v-on:click="getData()"> 
      Submit 
    </button>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Home',
  data() {
   return {
     textWord: null  
   } 
  },
  methods: {
    getData() {
      console.log(this.textWord);  
    }
  }
}
</script>
