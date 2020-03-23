<template>
	<view>
		<view class="top_bar">
			<text @tap="change(1)">正在进行</text>
			<text @tap="change(2)">已结束</text>
		</view>
		<view class="main">
		</view>
		<view class="bottom_tabbar">
			
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {

			}
		},
		onLoad() {

		},
		methods: {
			change(e){
				console.log(e)
			}
		}
	}
</script>

<style lang="scss" scoped>
	.top_bar{
		display: flex-inline;
		text-align: center;
		text{
			margin-left:66.5pt ;
			font-size: 14pt;

		}
	}

</style>
