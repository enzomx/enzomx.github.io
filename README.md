# enzomx.github.io


Simple responsive radio player template HTML5, CSS, JS, Bootstrap, Google fonts.



HTML HEAD:

```
		<meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=no" />
		<link rel="stylesheet" href="assets/css/main.css" />
		        <!-- Google material icons -->
				<link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">\
        <!--  bootstrap original       -->
		<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css" integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk" crossorigin="anonymous">
		
		<noscript><link rel="stylesheet" href="assets/css/noscript.css" /></noscript>

```

HTML BODY:



```
<div class="fixed-bottom container-fluid" id="menu-bottom">
	<div>
					
	<button class="btn btn-info" onclick="document.getElementById('player').play()" style="background-color: azure; ">
		<span class="material-icons md-36" onclick="document.getElementById('player').play()" style="color: olivedrab;">
			play_arrow
						
		</span>
	</button>
	
	<button class="btn btn-info" onclick="document.getElementById('player').pause()" style="background-color: azure;">
		<span class="material-icons md-36" style="color: olivedrab;">
								pause
		</span>
	</button>
	<button class="btn btn-info" onclick="document.getElementById('player').volume+=0.1" style="background-color: azure;">
		<span class="material-icons md-36" style="color: olivedrab;">
								volume_up
		</span>
	</button>
	<button class="btn btn-info" onclick="document.getElementById('player').volume-=0.1" style="background-color: azure;">
		<span class="material-icons md-36" style="color: olivedrab;">
								volume_down
		</span>
	</button>
	<span style="color: palegoldenrod;">
		<img src="images/logo-player2.png">
	</span>

	</div> 
	<audio id="player" src="https://streamingv2.shoutcast.com/altavozlive" type="audio/mpeg">

							
	</audio>
					
					
</div>
	
			<!-- Scripts -->

			<script src="assets/js/jquery.min.js"></script>
			<script src="assets/js/jquery.scrollex.min.js"></script>
			<script src="assets/js/jquery.scrolly.min.js"></script>
			<script src="assets/js/browser.min.js"></script>
			<script src="assets/js/breakpoints.min.js"></script>
			<script src="assets/js/util.js"></script>
			<script src="assets/js/main.js"></script>

			<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" 					crossorigin="anonymous"></script>
			<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-											Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
			<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js" integrity="sha384-											OgVRvuATP1z7JjHLkuOU7Xw704+h835Lr+6QL9UvYjZE3Ipu6Tp75j7Bh/kR0JKI" crossorigin="anonymous"></script>

```
