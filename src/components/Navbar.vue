<template>
	<div class="adminnavbar">
		<ul class="menu">
			<li>
				<a href="">
					<span class="icon"></span>
					<span>首页</span>
				</a>
			</li>
			<li>
				<a href="">
					<span class="icon"></span>
					<span>侧栏</span>
				</a>
			</li>
			<li>
				<a href="">
					<span class="icon"></span>
					<span>中心内容</span>
				</a>
			</li>
			<li>
				<a href="">
					<span class="icon"></span>
					<span>GG</span>
				</a>
			</li>
		</ul>
	</div>
</template>
<script></script>
<style>
	.adminnavbar{
		background: #485b79;
		background: url(../assets/headerbg.png);
		box-shadow: inset 0 1px 0 #50627f;
		min-height: 50px;
		overflow: hidden;
		border-bottom: 5px solid #fb9337;
		position: relative;
	}
	.adminnavbar ul.menu{
		border-right: 1px solid #576a85;
		list-style: none;
		/*display: inline-block;*/
		overflow: hidden;
	}
	.adminnavbar ul.menu li{
		float: left;
		display: inline-block;
		border-left: 1px solid #576a85;
		border-right: 1px solid #394962;
	}
	.adminnavbar ul.menu a{
		min-width: 80px;
		text-align: center;
		display: block;
		color: #fff;
		padding: 17px 10px;
		text-decoration: none;
	}
</style>