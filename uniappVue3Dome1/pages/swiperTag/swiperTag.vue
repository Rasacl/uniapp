<template>
	<view>
		<swiper :indicator-dots="true" :autoplay="true" :interval="3000" :duration="1000" circular>
			<swiper-item>
				<view class="swiper-item">1111111</view>
			</swiper-item>
			<swiper-item>
				<view class="swiper-item">222222</view>
			</swiper-item>
			<swiper-item>
				<view class="swiper-item">333333</view>
			</swiper-item>
			<swiper-item>
				<view class="swiper-item">444444</view>
			</swiper-item>
		</swiper>
	</view>
</template>

<script setup>
</script>

<style lang="scss">
swiper{
	width: 100vw;
	height: 200px;
	border: 1px solid red;
	swiper-item{
		width: 100%;
		height: 100%;
		background-color: palegreen;
	}
	swiper-item:nth-child(2n){
		background-color: violet;
	}
}
</style>
