<template>    
<BaseCard>
      <h1>Title 1</h1>
      <p>Content for the first card.</p>
    </BaseCard>
</template>

<script>
import BaseCard from './components/BaseCard.vue';

export default {
  name: 'App',
  components: {
    BaseCard
  }
}
</script>

<style>
body{
  margin: 0;
 
 
}
#app {
  padding: 100px;
  width: 100vw;
  min-height: 100vh;
  font-family: 'Roboto', sans-serif;
  background: radial-gradient(71.11% 100% at 50% 0%, #020204 14.6%, #011F35 100%);
  box-sizing: border-box;
 

}
</style>
