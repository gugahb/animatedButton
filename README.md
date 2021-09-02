# animatedButton

Vi no IG do Sujeito Programador

<svg fill="none" viewBox="0 0 400 400" width="400" height="400" xmlns="http://www.w3.org/2000/svg">
    <foreignObject width="100%" height="100%">
        <div xmlns="http://www.w3.org/1999/xhtml">
            <style>
body {
  background-color: black;
}
.container {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
a {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 190px;
  height: 45px;
  text-decoration: none;
  color: white;
  background-color: rgb(0, 13, 128);
  font-size: 1.5rem;
  letter-spacing: 2px;
  overflow: hidden;
  font-family: sans-serif;
  border-radius: 2px;
}
span {
  position: relative;
  display: block;
  transition: 0.3s ease;
}

span::before {
content: attr(data);
position: absolute;
transform: translateY(40px);
}

.container:hover span {
transform: translateY(-40px);
color: rgb(0, 255, 242);
}

.container span:nth-child(1) {
transition-delay: 0.05s;
}

.container span:nth-child(2) {
transition-delay: 0.15s;
}

.container span:nth-child(3) {
transition-delay: 0.25s;
}

.container span:nth-child(4) {
transition-delay: 0.35s;
}

.container span:nth-child(5) {
transition-delay: 0.35s;
}

.container span:nth-child(6) {
transition-delay: 0.25s;
}

.container span:nth-child(7) {
transition-delay: 0.15s;
}

</style>
           <div class="container">
    <h1>Passe o mouse</h1>
        <a href="#">
            <span data="G">G</span>
            <span data="u">u</span>
            <span data="s">s</span>
            <span data="t">t</span>
            <span data="a">a</span>
            <span data="v">v</span>
            <span data="o">o</span>
        </a>
    </div>
        </div>
    </foreignObject>
</svg>

<svg fill="none" viewBox="0 0 800 400" width="800" height="400" xmlns="http://www.w3.org/2000/svg">
	<foreignObject width="100%" height="100%">
		<div xmlns="http://www.w3.org/1999/xhtml">
			<style>
				@keyframes rotate {
					0% {
						transform: rotate(3deg);
					}
					100% {
						transform: rotate(-3deg);
					}
				}
				@keyframes gradientBackground {
					0% {
						background-position: 0% 50%;
					}
					50% {
						background-position: 100% 50%;
					}
					100% {
						background-position: 0% 50%;
					}
				}
				@keyframes fadeIn {
					0% {
						opacity: 0;
					}
					66% {
						opacity: 0;
					}
					100% {
						opacity: 1;
					}
				}
				.container {
					font-family:
						system-ui,
						-apple-system,
						'Segoe UI',
						Roboto,
						Helvetica,
						Arial,
						sans-serif,
						'Apple Color Emoji',
						'Segoe UI Emoji';
					display: flex;
					flex-direction: column;
					align-items: center;
					justify-content: center;
					margin: 0;
					width: 100%;
					height: 400px;
					background: linear-gradient(-45deg, #fc5c7d, #6a82fb, #05dfd7);
					background-size: 600% 400%;
					animation: gradientBackground 10s ease infinite;
					border-radius: 10px;
					color: white;
					text-align: center;
				}
				h1 {
					font-size: 50px;
					line-height: 1.3;
					letter-spacing: 5px;
					text-transform: uppercase;
					text-shadow:
						0 1px 0 #efefef,
						0 2px 0 #efefef,
						0 3px 0 #efefef,
						0 4px 0 #efefef,
						0 12px 5px rgba(0, 0, 0, 0.1);
					animation: rotate ease-in-out 1s infinite alternate;
				}
				p {
					font-size: 20px;
					text-shadow: 0 1px 0 #efefef;
					animation: 5s ease 0s normal forwards 1 fadeIn;
				}
			</style>
			<div class="container">
				<h1>Made with HTML &amp; CSS<br/>not an animated GIF</h1>
				<p>Click to see the source</p>
			</div>
		</div>
	</foreignObject>
</svg>
