<script>
import AppTitle from './components/AppTitle.vue';
export default { components:{
  AppTitle,
}}
</script>

<template>
  <div class="vitellino">
    <h1>
      manzotin
    </h1>
    <h2>vit-hello</h2>
  </div>
  <AppTitle></AppTitle>
 
</template>

<style scoped>
.vitellino{
  display: flex;
  flex-direction: column;
  width: 100%;
  height: 100%;
  
  text-decoration: underline;
  text-transform: uppercase;
  background-color: darkblue;
  border-radius: 20px;
  text-align: center;
  padding: 40px;
  color: rgb(31, 226, 70);
  font-family:   sans-serif ;
}
 

</style>
