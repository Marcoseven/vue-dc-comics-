<template>
	<!-- #SiteHeader -->
	<header id="SiteHeader">
		<div class="container">
			<!-- .row -->
			<div class="row">
				<div>
					<img src="../assets/img/dc-logo.png" alt="immagine logo dc" />
				</div>
				<div>
					<!-- .menu -->
					<nav class="menu">
						<ul class="row">
							<li><a href="#">CHACTERS</a></li>
							<li><a href="#">COMICS</a></li>
							<li><a href="#">MOVIES</a></li>
							<li><a href="#">TV</a></li>
							<li><a href="#">GAMES</a></li>
							<li><a href="#">COLLECTIBLES</a></li>
							<li><a href="#">VIDEOS</a></li>
							<li><a href="#">FANS</a></li>
							<li><a href="#">NEWS</a></li>
							<li><a href="#">SHOP</a></li>
						</ul>
					</nav>
					<!-- /.menu -->
				</div>
			</div>
			<!-- /.row -->
		</div>
	</header>
	<!-- /#SiteHeader -->
</template>

<script></script>

<style lang="scss">
@import "../assets/scss/common.scss";
@import "../assets/scss/variables.scss";
#SiteHeader {
	height: auto;
	margin-bottom: 0.5rem;

	.row {
		justify-content: space-between;
		align-items: center;
		img:hover {
			cursor: pointer;
		}
	}

	.menu {
		a {
			margin: 0 0.5rem;
			padding: 2rem 0;
			color: #333;
			&:hover {
				color: $brand_color;
				border-bottom: 5px solid $brand_color;
			}
		}
	}
}
</style>
