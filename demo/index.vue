<template>
	<view class="content">
		<an-upload-img></an-upload-img>
	</view>
</template>

<script>
	import uniGrid from '@/components/uni-grid/uni-grid.vue'
	import uniIcon from '@/components/uni-icon/uni-icon.vue'
	import anUploadImg from '@/components/an-uploadImg/an-uploadImg'
	
	export default {
		components:{
			anUploadImg
		},
		data() {
			return {
				
			}
		},
		methods: {
			
		}
	}
</script>

<style>
	.content{
		background-color: #f2f2f2;
	}
</style>
