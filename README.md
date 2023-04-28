<!DOCTYPE html>
<html>
<head>
	<title>My Animated README</title>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css">
	<style>
		body {
			font-family: Arial, sans-serif;
			color: #fff;
			background-color: #24292e;
			padding: 0;
			margin: 0;
			overflow: hidden;
		}
		.container {
			max-width: 800px;
			margin: 0 auto;
			padding: 40px;
			background-color: rgba(0, 0, 0, 0.5);
			box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
			border-radius: 5px;
			animation: pulse 2s infinite;
		}
		h1 {
			font-size: 48px;
			font-weight: bold;
			margin: 0 0 20px;
			color: #fff;
			animation: slideInDown 1s;
		}
		p {
			font-size: 16px;
			line-height: 1.5;
			margin: 0 0 20px;
			color: #fff;
			animation: fadeIn 2s;
		}
		@keyframes pulse {
			0% {
				box-shadow: 0 0 0 0 rgba(0, 0, 0, 0.5);
			}
			70% {
				box-shadow: 0 0 0 10px rgba(0, 0, 0, 0);
			}
			100% {
				box-shadow: 0 0 0 0 rgba(0, 0, 0, 0);
			}
		}
		@keyframes slideInDown {
			from {
				transform: translateY(-100%);
			}
			to {
				transform: translateY(0%);
			}
		}
		@keyframes fadeIn {
			from {
				opacity: 0;
			}
			to {
				opacity: 1;
			}
		}
	</style>
</head>
<body>
	<div class="container animate__animated animate__fadeIn">
		<h1>My Animated README</h1>
		<p>Welcome to my GitHub profile! This is an example of an animated README.md created with HTML and CSS animations.</p>
	</div>
</body>
</html>
