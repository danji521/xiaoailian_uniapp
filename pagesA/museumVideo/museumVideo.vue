<template>
	<view class="museumVideos">
		<view class="title">
			<view>视频</view>
			<view></view>
		</view>
		<view class="museum-album-list" v-for="index in 6" @click="museumVideosDetail()">
			<image src="../../static/home_6.png" mode=""></image>
			<view class="museum-album-list_number">
				<view>普吉岛之旅</view>
				<view>(18)</view>
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {

			};
		},
		methods: {
			museumVideosDetail() {
				uni.navigateTo({
					url: '/pagesA/museumVideosDetail/museumVideosDetail'
				})
			}
		}

	}
</script>

<style lang="scss">
	.museumVideos {
		padding: 0 20rpx;

		.title {
			display: flex;
			justify-content: space-between;
			align-items: center;
			font-size: 35rpx;
			padding-left: 10rpx;
			margin: 20rpx 0;
			border-left: 9rpx solid #ff6c98;
		}

		.title :nth-child(2) {
			color: #bababa;
		}
	}

	.museum-album-list {
		margin: 10rpx 0;
		margin-right: 3.33333333%;
		width: 30%;
		float: left;
		font-size: 30rpx;
		color: #7e7e7e;

		.museum-album-list_number {
			display: flex;
			justify-content: space-between;
			align-items: center;
		}

		image {
			width: 100%;
			height: 200rpx;
		}
	}
</style>
