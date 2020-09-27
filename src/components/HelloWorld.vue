<template>
  <div class="container-fluid p-3 text-white">
    <h1 class="display-1"><b>Life-Guards</b></h1>
    <button class="btn" id="btn"><b>Sign-Up</b></button>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld'
}
</script>
<style scoped>
div{
  text-align: center;
  background: #1abc9c;
}
#btn{
  position: absolute;
  right: 50px;
  top: 50px;
  width: 70px;
  background-color:rgb(255, 255, 255);
}
#btn:hover{
   box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
}
</style>
