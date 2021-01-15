<template>
	<view class="content">
		<view>
            <text class="title">{{title}}</text>
        </view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: '首页'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	@import url("../../static/font/iconfont.css");
	.content {
		text-align: center;
		height: 400upx;
	}
    .logo{
        height: 200upx;
        width: 200upx;
        margin-top: 200upx;
    }
	.title {
		font-size: 36upx;
		color: #8f8f94;
	}
</style>
