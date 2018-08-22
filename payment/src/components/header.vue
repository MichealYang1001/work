<template>
	<header class="clearfix">
		<div class="header-order">
			<div>订单号：91512232</div>
			<div>商户：比特大陆有限公司</div>
		</div>
		<div class="header-money"><span>198.00</span>  US</div>
	</header>
</template>
<script>
export default {
  	props: {
    	orderId: Number,
    	merchant: String
  	}
}
</script>
<style lang="scss">
	header {
		margin-top: 30px;
	}
	header >div{
		float: left;
	}
	.header-order {
		float: left;
		font-size: 13px;
	}
	.header-order >div:last-child {
		margin-top: 5px;
	}
	.header-money {
		float: right;
		margin-top: 5px;
	}
	.header-money span {
		font-size: 20px;
		color: rgba(254,106,0);
	}
</style>