<template>
	<div id="alltarget">
		<div class="bg_box"></div>
		<div class="alltarget_title tal">
			<p>实时监控</p>
			<h5>1#</h5>
		</div>
		<div class="alltarget_main">
			<mt-swipe :auto="5000000">
			  <mt-swipe-item>
			  	<div class="alltarget_list_box1 alltarget_list_box">
			  		<ul>
			  			<li>
			  				<h5><span class="bgLinear1 bgLinear wsd-52"></span></h5>
			  				<h4>温度</h4>
			  				<p>0.00</p>
			  			</li>
			  			<li>
			  				<h5><span class="bgLinear2 bgLinear wsd-64"></span></h5>
			  				<h4>湿度</h4>
			  				<p>0.00</p>
			  			</li>
			  			<li>
			  				<h5><span class="bgLinear3 bgLinear wsd-69"></span></h5>
			  				<h4>甲苯</h4>
			  				<p>0.00</p>
			  			</li>
			  			<li>
			  				<h5><span class="bgLinear4 bgLinear  wsd-77"></span></h5>
			  				<h4>苯</h4>
			  				<p>0.00</p>
			  			</li>
			  			<li>
			  				<h5><span class="bgLinear5 bgLinear  wsd-90 f-38"></span></h5>
			  				<h4>二甲苯</h4>
			  				<p>0.00</p>
			  			</li>
			  			
			  			<li>
			  				<h5><span class="bgLinear6 bgLinear  wsd-65"></span></h5>
			  				<h4>甲醇</h4>
			  				<p>0.00</p>
			  			</li>
			  			<li>
			  				<h5><span class="bgLinear7 bgLinear  wsd-88"></span></h5>
			  				<h4>二氧化碳</h4>
			  				<p>0.00</p>
			  			</li>
			  			<li>
			  				<h5><span class="bgLinear8 bgLinear  wsd-89"></span></h5>
			  				<h4>二氧化硫</h4>
			  				<p>0.00</p>
			  			</li>
			  		</ul>
			  	</div>
			  </mt-swipe-item>
			  <mt-swipe-item>
			  	<div class="alltarget_list_box2 alltarget_list_box">
			  		<li>
		  				<h5><span class="bgLinear9 bgLinear  wsd-91"></span></h5>
		  				<h4>丙酮</h4>
		  				<p>0.00</p>
		  			</li>
		  			<li>
		  				<h5><span class="bgLinear10 bgLinear  wsd-54"></span></h5>
		  				<h4>异丙醇</h4>
		  				<p>0.00</p>
		  			</li>
		  			<li>
		  				<h5><span class="bgLinear11 bgLinear  wsd-45"></span></h5>
		  				<h4>乙醇乙酯</h4>
		  				<p>0.00</p>
		  			</li>
			  	</div>
			  </mt-swipe-item>
			</mt-swipe>
		</div>
	</div>
</template>

<script>
export default {
  data () {
    return {
      msg: '',
    }
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
	.bgLinear{
		font-size: 27px;
		color: #fff;
		line-height: 38px;
	}
	.f-38{
		font-size: 38px;
	}
	.bgLinear:before{
		
		font-weight: 400;
	}
	.icon1{
		width: 100px;
		height: 100px;
		font-size: 50px;
	}
	#alltarget{
		position: relative;
	}
	.bg_box{
		background: #00aef9;
		height: 200px;
		position: absolute;
		z-index: 0;
		left: -11px;
		top: 0;
		right: -11px;
	}
	.alltarget_title,.alltarget_main{
		z-index: 1;
		position: relative;
	}
	.alltarget_title p{
		font-size: 15px;
		color: #fff;
		padding-top: 15px;
		padding-bottom: 10px;
		line-height: 1;
		font-weight: 600;
	}
	.alltarget_title h5{
		color: #fff;
		font-size: 12px;
		line-height: 1;
		padding-bottom: 15px;
	}
	.alltarget_main{
		height: 220px;
		border-radius: 5px;
		background: #fff;
	}
	.alltarget_list_box{
		padding-top: 20px;
	}
	.alltarget_list_box li{
		width: 25%;
		float: left;
		margin-bottom: 14px;
	}
	.alltarget_list_box li h5 {
		height: 38px;
	}
	.alltarget_list_box li h5 span{
		width: 38px;
		height: 38px;
		border-radius: 50%;
		display: inline-block;
	}
	.alltarget_list_box li h4{
		font-size: 15px;
		line-height: 32px;
	}
	.alltarget_list_box li p{
		font-size: 12px;
		line-height: 1;
	}
	.bgLinear1{
background: -webkit-linear-gradient(#ffa197, #fd75b7); /* Safari 5.1 - 6.0 */
background: -o-linear-gradient(#ffa197, #fd75b7); /* Opera 11.1 - 12.0 */
background: -moz-linear-gradient(#ffa197, #fd75b7); /* Firefox 3.6 - 15 */
background: linear-gradient(#ffa197, #fd75b7); /* 标准的语法 */
/*box-shadow: 0px 1px 5px 1px  rgba(253,117,183,0.3);*/
}
.bgLinear2{
background: -webkit-linear-gradient(#fcb479, #fc9970); /* Safari 5.1 - 6.0 */
background: -o-linear-gradient(#fcb479, #fc9970); /* Opera 11.1 - 12.0 */
background: -moz-linear-gradient(#fcb479, #fc9970); /* Firefox 3.6 - 15 */
background: linear-gradient(#fcb479, #fc9970); /* 标准的语法 */
}
.bgLinear3{
background: -webkit-linear-gradient(#f48de8, #be88f7); /* Safari 5.1 - 6.0 */
background: -o-linear-gradient(#f48de8, #be88f7); /* Opera 11.1 - 12.0 */
background: -moz-linear-gradient(#f48de8, #be88f7); /* Firefox 3.6 - 15 */
background: linear-gradient(#f48de8, #be88f7); /* 标准的语法 */
}
.bgLinear4{
background: -webkit-linear-gradient(#fdaf6f, #fb9970); /* Safari 5.1 - 6.0 */
background: -o-linear-gradient(#fdaf6f, #fb9970); /* Opera 11.1 - 12.0 */
background: -moz-linear-gradient(#fdaf6f, #fb9970); /* Firefox 3.6 - 15 */
background: linear-gradient(#fdaf6f, #fb9970); /* 标准的语法 */
}
.bgLinear5{
background: -webkit-linear-gradient(#e284f2, #fa8ce5); /* Safari 5.1 - 6.0 */
background: -o-linear-gradient(#e284f2, #fa8ce5); /* Opera 11.1 - 12.0 */
background: -moz-linear-gradient(#e284f2, #fa8ce5); /* Firefox 3.6 - 15 */
background: linear-gradient(#e284f2, #fa8ce5); /* 标准的语法 */
}
.bgLinear6{
background: -webkit-linear-gradient(#b4daff, #8299f9); /* Safari 5.1 - 6.0 */
background: -o-linear-gradient(#b4daff, #8299f9); /* Opera 11.1 - 12.0 */
background: -moz-linear-gradient(#b4daff, #8299f9); /* Firefox 3.6 - 15 */
background: linear-gradient(#b4daff, #8299f9); /* 标准的语法 */
}
.bgLinear7{
background: -webkit-linear-gradient(#fca37b, #ffb181); /* Safari 5.1 - 6.0 */
background: -o-linear-gradient(#fca37b, #ffb181); /* Opera 11.1 - 12.0 */
background: -moz-linear-gradient(#fca37b, #ffb181); /* Firefox 3.6 - 15 */
background: linear-gradient(#fca37b, #ffb181); /* 标准的语法 */
}
.bgLinear8{
background: -webkit-linear-gradient(#afb9ff, #91cbfd); /* Safari 5.1 - 6.0 */
background: -o-linear-gradient(#afb9ff, #91cbfd); /* Opera 11.1 - 12.0 */
background: -moz-linear-gradient(#afb9ff, #91cbfd); /* Firefox 3.6 - 15 */
background: linear-gradient(#afb9ff, #91cbfd); /* 标准的语法 */
}
.bgLinear9{
background: -webkit-linear-gradient(#ff80b3, #fd866e); /* Safari 5.1 - 6.0 */
background: -o-linear-gradient(#ff80b3, #fd866e); /* Opera 11.1 - 12.0 */
background: -moz-linear-gradient(#ff80b3, #fd866e); /* Firefox 3.6 - 15 */
background: linear-gradient(#ff80b3, #fd866e); /* 标准的语法 */
}
.bgLinear10{
background: -webkit-linear-gradient(#7466f9, #8cadfe); /* Safari 5.1 - 6.0 */
background: -o-linear-gradient(#7466f9, #8cadfe); /* Opera 11.1 - 12.0 */
background: -moz-linear-gradient(#7466f9, #8cadfe); /* Firefox 3.6 - 15 */
background: linear-gradient(#7466f9, #8cadfe); /* 标准的语法 */
}
.bgLinear11{
background: -webkit-linear-gradient(#87adf4, #8bd2ee); /* Safari 5.1 - 6.0 */
background: -o-linear-gradient(#87adf4, #8bd2ee); /* Opera 11.1 - 12.0 */
background: -moz-linear-gradient(#87adf4, #8bd2ee); /* Firefox 3.6 - 15 */
background: linear-gradient(#87adf4, #8bd2ee); /* 标准的语法 */
}
</style>
