<template>
	<view style="background-color: #FFFFFF;">
<!-- 		<view>
			<cu-custom bgColor="bg-gradual-blue" :isBack="true" class="status_bar">
				<block slot="content">训练规则</block>
			</cu-custom>
		</view> -->
		<image style="width: 750rpx;" src="../../../static/xizi_img/top.png" mode=""></image>
		<text>什么是训练陪伴人？

			就是教你的陪伴人角色说话！通过设置关键词和输入你希望对方回复的内容，陪伴人会根据算法让你的角色学会说这句话



			如何训练陪伴人？

			点击底部的“立即提交”即可参与角色训练。

			提交训练后会由审核官进行审核，审核通过后训练内容就会进入人物智能库中，所有使用该人物的用户都有机会收到你提交的训练内容(๑•̀ㅂ•́)و✧



			心动值是什么？

			你参与训练创作的内容，或者你上传的表情包，被其他用户看到点击心动后，你就会收到心动值。

			心动值代表用户对你创作内容的喜欢。
		</text>
		<button @click="back" type="primary">返回</button>
	</view>
</template>

<script>
	export default {
		data() {
			return {

			}
		},
		methods: {
			back(){
				uni.navigateBack({
					delta:1
				})
			}

		}
	}
</script>

<style>
	@import url("../../../colorui/main.css");
	@import url("../../../colorui/icon.css");

	.status_bar {
		height: var(--status-bar-height);
		width: 100%;
	}
</style>
