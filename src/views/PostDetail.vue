<template>
	<div id="main">
		<PostInfo id="post"></PostInfo>
	</div>
</template>

<script>
import PostInfo from '@/components/PostInfo.vue'

export default {
	name: 'PostDetail',
	components: {
		PostInfo,
	},
}
</script>

<style>
ul,
ol,
li {
	list-style-type: none;
	padding: 0; /* 패딩을 제거하려면 추가 */
	margin: 0; /* 마진을 제거하려면 추가 */
}

#app {
	display: flex;
}

#main {
	display: flex;
	margin-left: auto;
	margin-top: 10%;
	align-items: center;
	justify-content: center;
}

#post {
	width: 100%;
	text-align: center;
}
</style>
