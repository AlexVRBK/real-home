<template>
	<div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="carousel">
		<ol class="carousel-indicators home__carousel-indicators">
			<li data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active"></li>
			<li data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1"></li>
			<li data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2"></li>
		</ol>
		<div class="carousel-inner">
			<div class="carousel-item active">
				<img src="../assets/images/slide.png" class="d-block w-100" alt="" />
				<div class="carousel-caption d-none d-md-block">
					<h5>120 Anastasia Avenue, Coral Gables</h5>
					<p>$625,000</p>
					<button type="button" class="btn btn-outline-dark">MORE INFO</button>
				</div>
			</div>
			<div class="carousel-item">
				<img src="../assets/images/slide.png" class="d-block w-100" alt="" />
				<div class="carousel-caption d-none d-md-block">
					<h5>Second slide label</h5>
					<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
				</div>
			</div>
			<div class="carousel-item">
				<img src="../assets/images/slide.png" class="d-block w-100" alt="" />
				<div class="carousel-caption d-none d-md-block">
					<h5>Third slide label</h5>
					<p>Praesent commodo cursus magna, vel scelerisque nisl consectetur.</p>
				</div>
			</div>
		</div>
	</div>
</template>

<style lang="scss">
	.home {
		&__carousel-indicators {
			bottom: 200px;
		}
	}
</style>