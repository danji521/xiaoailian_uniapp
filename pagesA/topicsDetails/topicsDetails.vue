<template>
	<view class="topic">
		<view class="nav">
			<image src="../../static/findDetails_0.png" mode=""></image>
		</view>
		<view class="title">
			3个脱单秘籍，要不要这么简单
		</view>

		<view class="text">
			情人节其实很多单身的男女一样情人节其实很多单身的男女一
			样情人节其情人节其实很多单身的男女一样情人节其实很多单身
			的男女一样情人节其情人节其实很多单身的男女一样情人节其实很
			多单身的男女一样情人节其实很多单身的男女一样情人节其实很多单
			身的男女一样
		</view>
		<navigator url="/pagesA/discuss/discuss">
			<view class="bnt">
				+添加讨论
			</view>
		</navigator>
		<view class="user">
			<view class="user-title">精彩分享</view>
			<view class="user-box">
				<view class="user-box_img">
					<image src="../../static/home_5.png" mode=""></image>潇潇 <view class="pink">（很重要）</view>
				</view>
				<view class="user-box_day">2019/12/07</view>
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {

			};
		}
	}
</script>

<style lang="scss">
	.nav {
		width: 100%;
		height: 480rpx;

		image {
			width: 100%;
			height: 100%;
		}
	}

	.title {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 108rpx;
		font-size: 45rpx;
	}

	.text {
		padding: 0 20rpx;
		color: #999999;
		font-size: 35rpx;
		line-height: 60rpx;
		text-indent: 60rpx;
	}


	.bnt {
		display: flex;
		justify-content: center;
		align-items: center;
		position: fixed;
		font-size: 30rpx;
		right: 0;
		bottom: 126rpx;
		color: #FFFFFF;
		width: 224rpx;
		height: 88rpx;
		border-top-left-radius: 50rpx;
		border-bottom-left-radius: 50rpx;
		background-image: linear-gradient(to right, #ff82ba, #ffb1c4);
	}

	.user {
		position: fixed;
		bottom: 0;
		width: 100%;
	}

	.user-title {
		padding-left: 20rpx;
		font-size: 35rpx;
		height: 60rpx;
	}

	.user-box {
		display: flex;
		justify-content: space-between;
		align-items: center;
		height: 126rpx;
		font-size: 30rpx;
		border-top: 2rpx solid #f5e6ed;
	}

	.user-box_img {
		display: flex;
		align-items: center;
		padding-left: 20rpx;
		font-size: 30rpx;

		image {
			margin-right: 16rpx;
			width: 46rpx;
			height: 46rpx;
			border-radius: 50%;
		}

		.pink {
			color: #F06C7A;
			font-size: 30rpx;
		}
	}

	.user-box_day {
		padding-right: 20rpx;
		color: #999999;
		font-size: 30rpx;
	}
</style>
