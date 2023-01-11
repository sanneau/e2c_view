<template>
  <div id="container" :class="flex-container">
    <div id="one"><p>Cadence réel</p><vue-gauge :refid="'type-unique-id'" :options="{'needleValue':85,'arcDelimiters':[10,36,78],'arcLabels':['3%','5%','8%'], 'arcColors':['green','green','orange','red']}"></vue-gauge></div>
    <div id="two"><p>Défaut</p><vue-gauge :refid="'type-unique-id'" :options="{'needleValue':85,'arcDelimiters':[10,36,78],'arcLabels':['3%','5%','8%'], 'arcColors':['green','green','orange','red']}"></vue-gauge></div>
  </div>
</template>
  
<script>
  import VueGauge from 'vue-gauge';
  export default {
    components: { VueGauge },
  }
 
</script>
  
<style scoped>
#container {
  display: flex;
  float: left;
  flex-direction: column;
  border-style: solid;
}

#one,
#two
{
  width: 250px;
  height: 180px;
  border: solid;
}
</style>
  