<template>
  <div class="header">
    <div header-left>
		<span class="iconfont">&#xe624;</span> <!--左箭头的16进制码-->
	</div>
    <div header-input>
		<span class="iconfont">&#xe632;</span>
		内容
		</div>
    <div header-right>
		城市
		<span class="iconfont">&#xe64a;</span></div>
  </div>
</template>

<script>
  export default {
    data(){return {}},
    components:{
		name:'Header'
	},
    mounted(){},
    updated(){},
    methods:{}
  }
</script>

<style scoped>
  .header{
	display: flex;
	 justify-content: space-between;
	 height: .86rem;
	 line-height: .86rem;
	 background: #00bcd4;
	 color: #fff;
	 text-align: center;
	 width:100%; 
	 /* position:relative; top:0;left:0; z-index:2; */
  }
  .header-left{
	  width: .64rem;
	  
	  /* float: left; */
  }
   .header .header-input{
   	  flex: 1;
   	  border: 1px solid #red;
   	  height: .64rem;
   	  width: 100rem;
   	  line-height: .64rem;
   	  margin-top: .12rem;
   	  margin-left: .2rem;
   	  padding-left: .2rem;
   	  background: #fff;
   	  border-radius: .1rem;
   	  color: #ccc;   	  
   }
  .header .header-right{
  	  min-width: 1.04rem;
  	  padding: 0 .1rem;
  	  text-align: center;
  	  color: #fff;
	  /* float: right; */
  }
</style>
