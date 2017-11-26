<template>
	<div id="index-care">
		<div class="login-tip" v-if='login'>
			<img src="./img/q2.png">
			<span>搞笑逗比私人订制</span>
			<span>登陆账户关注你喜欢的TA</span>
			<p>
				<router-link to='/my'>登陆传送门</router-link>
			</p>
		</div>
	</div>
</template>
<script>
	export default {
		data(){
			return {
				login:true,
			}
		},
	}
</script>
<style lang='less' scoped>
	@import '~@/assets/css/care.less';
</style>