<template>
	<div class="admincontent">
		<div class="contentcenter">
			我是内容
		</div>
	</div>
</template>
<script></script>
<style>
	.admincontent{
		overflow: auto;
		padding: 10px;
		height: 100%;
		position: relative;
	}
	.admincontent:after{
		clear: both;
	}
	.contentcenter{
		position: absolute;
		left: 50%;
		top: 50%;
		transform: translate(-50%, -50%);
	}
</style>