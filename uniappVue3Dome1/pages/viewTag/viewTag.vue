<template>
	<view class="box" hover-class="boxHover" hover-stay-time="10">view布局标签
	
	<view class="innerBox" hover-class="innerHover" hover-stop-propagation>内部元素</view>
	</view>
</template>

<script setup>

</script>

<style lang="scss">
.box{
	width: 200px;
	height: 200px;
	background-color: gray;
	.innerBox{
		width: 150px;
		height: 150px;
		background-color: yellowgreen;
	}
	
	.innerHover{
		background-color: blueviolet;
	}
}
.boxHover{
	background-color: red;
}
</style>
