<template>
	<view class="content">
		<view class="todo-header">
			<view class="header_left">
				<text>全部</text>
				<text>10条</text>
			</view>
			<view class="header_right">
                <view class="item">全部</view>
				<view class="item">代办</view>
				<view class="item">已完成</view>
			</view>
		</view>

	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: 'Hello'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	.todo-header{
		display: flex;
		align-items: center;
		font-size: 12px;
		color: #333;
		height: 45px;
		box-shadow: -1px 1px 5px 0 rgba(0,0,0,0.1);
		background-color: #fff;
		padding: 0 15px;
	}
	.header_left{
		width: 100%;
	};
	.header_right{
		flex-shrink: 0;
		display: flex;
	}
	.item{
		padding: 0 5px;
	}

</style>
