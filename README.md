# slider
this is a css3 slider plugins
use it without javascript
use it without jQuery

#How to use it
1、include the slider.css file
<link rel="stylesheet" href="slider.css"/>

2、the html content like this
<pre>
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
			</div>
			<div class="slider-point">
				<label for="slide1"></label>
				<label for="slide2"></label>
				<label for="slide3"></label>
			</div>
		</section>
		</pre>
