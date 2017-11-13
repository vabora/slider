# slider
this is a css3 slider plugins
use it without javascript
use it without jQuery

# How to use it
1. include the slider.css file
`<link rel="stylesheet" href="slider.css"/>`
2. The html content like this

```
	<section class="slider">
			<div class="slides">
				<input checked="" id="slide1" type="radio" name="slide"/>
				<div class="slide" style="background-image:url(image url)">
					<div class="slide-title">
						<h1>page1</h1>
						<p>this is page1 content!</p>
						<a href="#">more</a>
					</div>
					<label class="slider-arrow-left" for="slide3"></label>
					<label class="slider-arrow-right" for="slide2"></label>
				</div>
				<label class="slider-point" style="--slide-id:1;--slide-num:3;" for="slide1"></label>
				<input id="slide2" type="radio" name="slide"/>
				<div class="slide" style="background-image:url(image url)">
					<div class="slide-title">
						<h1>page2</h1>
						<p>this is page2 content!</p>
						<a href="#">more</a>
					</div>
					<label class="slider-arrow-left" for="slide1"></label>
					<label class="slider-arrow-right" for="slide3"></label>
				</div>
				<label class="slider-point" style="--slide-id:2;--slide-num:3;" for="slide2"></label>
				<input id="slide3" type="radio" name="slide"/>
				<div class="slide" style="background-image:url(image url)">
					<div class="slide-title">
						<h1>page3</h1>
						<p>this is page3 content!</p>
						<a href="#">more</a>
					</div>
					<label class="slider-arrow-left" for="slide2"></label>
					<label class="slider-arrow-right" for="slide1"></label>
				</div>
				<label class="slider-point" style="--slide-id:3;--slide-num:3;" for="slide3"></label>
			</div>
		</section>
	
```
3. The result like this；
