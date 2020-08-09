# enzomx.github.io


Simple responsive radio player template HTML5, CSS, JS, Bootstrap, Google fonts.


```
<div class="fixed-bottom container-fluid" id="menu-bottom">
						<div>
					
							<button class="btn btn-info" onclick="document.getElementById('player').play()" style="background-color: azure; ">
								<span class="material-icons md-36" onclick="document.getElementById('player').play()" style="color: olivedrab;">
								play_arrow
								</span></button>
							<button class="btn btn-info" onclick="document.getElementById('player').pause()" style="background-color: azure;"><span class="material-icons md-36" style="color: olivedrab;">
								pause
								</span></button>
							<button class="btn btn-info" onclick="document.getElementById('player').volume+=0.1" style="background-color: azure;"><span class="material-icons md-36" style="color: olivedrab;">
								volume_up
								</span></button>
							<button class="btn btn-info" onclick="document.getElementById('player').volume-=0.1" style="background-color: azure;"><span class="material-icons md-36" style="color: olivedrab;">
								volume_down
								</span></button>
								<span style="color: palegoldenrod;">            <img src="images/logo-player2.png">



								</span>

						</div> 
						<audio id="player" src="https://streamingv2.shoutcast.com/altavozlive" type="audio/mpeg">

							
						</audio>
					
					
					</div>
```
