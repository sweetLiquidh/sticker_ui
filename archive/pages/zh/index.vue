<template>
  <div class="index-box" >
    <img class="img" src="../../assets/images/rr.gif" alt="" srcset="">
  </div>
</template>

<script>
export default {
    name:'archive-index',
    data(){
      return{
        // img:require('../assets/images/model.jpg')
      }
    }
}
</script>

<style scoped >
.index-box{
  box-sizing: border-box;
  height: 700px;
  background: #fff;
  border: 1px solid blue;
  margin-top: 80px;
}
.img{
  width: 800px;

}
</style>