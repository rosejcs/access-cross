<template>
  <div>
    <h1>123</h1>
    <div>
      <!-- <img src="http:" alt=""> -->
      <!-- <img src="//i.tianqi.com/index.php?c=code&id=12&icon=1&num=5&site=12" /> -->
      <!-- <iframe src="//i.tianqi.com/index.php?c=code&id=12&icon=1&num=5&site=12"></iframe> -->
    </div>
  </div>
</template>


<script>
export default {
  data(){
    return {}
  },
  created(){
    this.axios('https://www.tianqiapi.com/api/').then(res=>{
      console.log(res);
    })
  }
}
</script>

<style lang="" scope>
  
</style>