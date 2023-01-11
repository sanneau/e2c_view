<template>
    <VueGauge/>
</template>
    
<script>
  import VueGauge from './VueGauge.vue'

  export default {
  name: 'CardComposant',
  components: 
  { VueGauge }
}
   
</script>
    <!-- Add "scoped" attribute to limit CSS to this component only -->
    <style scoped>
    h3 {
      margin: 40px 0 0;
    }
    div.solid {
        border-style: solid;
    }
    ul {
      list-style-type: none;
      padding: 0;
    }
    li {
      display: inline-block;
      margin: 0 10px;
    }
    a {
      color: #42b983;
    }
    </style>
    