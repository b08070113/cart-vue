<template>
  <div id="detail">
    <div>detail</div>
  </div>
</template>

<script>
  

  export default {
		name: "Detail",
    components: {
      
    },
	}
</script>

<style scoped>
  #detail {
    height: 100vh;
    position: relative;
    z-index: 1;
    background-color: #fff;
  }

  .content {
    position: absolute;
    top: 44px;
    bottom: 60px;
  }

  .back-top {
    position: fixed;
    right: 10px;
    bottom: 65px;
  }
</style>
