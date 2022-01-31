<template>
	<div class="main">
		<div class="profile-header">
			<div class="profile-img">
				<img src="./assets/user.jpg" class="profile-pic" alt="" />
			</div>
			<h2>Joel Olawanle</h2>
			<span>Web developer"</span>
		</div>
		<div class="profile-info">
			<p>Joel Olawanle is a Frontend developer with expertise in vue.js and React.js alongside Jamstack frameworks like Nuxt, 
					Next.js and Gridsome. He is highly skilled at converting images/UI designs into frontend codes (UI developer). He is also a 
					Technical writer interested in making the web accessible to everyone by always looking for ways to give back to the tech community. 
					Furthermore, he is currently taking a deep dive into React and Headless CMS of which he is doing a lot of writing on as he learns 
					new things. He is a big fan of open source."
			</p>
		</div>
	</div>
</template>

<script>
	export default {
		name: 'App',
	};
</script>

<style>
	* {
		margin: 0;
		padding: 0;
		box-sizing: border-box;
	}

	body {
		font-family: Arial, Helvetica, sans-serif;
		min-height: 100vh;
		width: 100vw;
		background: rgb(9, 6, 32);
		color: #fff;
		margin: 0 auto;
	}

	.main {
		margin: 0 25%;
		padding: 100px;
		display: flex;
		flex-direction: column;
		align-items: center;
		gap: 20px;
	}

	@media (max-width: 500px) {
		.main {
			margin: 0 10%;
			padding: 30px 10px;
		}
	}

	.profile-header {
		display: flex;
		align-items: center;
		flex-direction: column;
	}

	img {
		max-width: 100%;
	}

	.profile-pic {
		width: 250px;
		border-radius: 50%;
		object-fit: cover;
		border: 5px solid #fff;
		margin-bottom: 15px;
	}

	h2 {
		font-size: 35px;
	}

	p {
		margin-top: 20px;
		font-size: 23px;
		text-align: center;
		color: rgb(223, 221, 221);
	}

	@media (max-width: 500px) {
		p {
			margin-top: 20px;
			font-size: 18px;
			text-align: center;
		}
	}

	.lang{
		padding: 10px;
	}
</style>
