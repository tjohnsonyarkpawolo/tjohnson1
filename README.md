<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="UTF-8">
		<meta name="viewport" content=width=divice-width, initial-scale=1.0">
		<title> HMB and TJY Scholarship web </title>
		<style>
			
				body {
					font-family: Arial, sans-serif;
					margin: 0;
					padding: 0;
					background-color: #c1c1c1;
					}
				header, footer {
					background-color: #333;
					color: #fff;
					text-align: center;
					padding: 10px 0;
					}
				header h1 {
					margin: 0;
					}
				  .container {
           				 max-width: 800px;
           				 margin: 20px auto;
           				 padding: 20px;
           				 background-color: #fff;
            				box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
       					 }
				img {
					width: 500px;
					height: 500px;
					display: block;
					margin: 20px auto;
					}
				form {
            				margin-top: 20px;
       					 }
        			label {
           				 display: block;
           				 margin-bottom: 5px;
        				}
        			input[type="text"],
        			input[type="email"] {
            				width: 100%;
            				padding: 10px;
            				margin-bottom: 10px;
            				border: 1px solid #ddd;
           				border-radius: 4px;
        				}
        			input[type="submit"] {
           				 padding: 10px 20px;
           				 background-color: #333;
            				color: #fff;
           				 border: none;
           				 border-radius: 4px;
           				 cursor: pointer;
        				}
        			input[type="submit"]:hover {
           				 background-color: #555;
        				}

				.error {
					color: red;
					margin-bottom: 10px;
					}
		</style>	
	</head>
		<body>
			<header>
			<h1> HMB and TJY SCHOLARSHIP CONSULTANTS </h1>
			</header>
			<div class="container">
			<p> Welcome to HMB and TJY Scholarship Consultants webpage. </p>
			<p> We offer the following scholarships: </p>
				<ul>
					<li>Fully funded Scholarship</li>
					<li>Full Scholarship</li>
				</ul>
				<p> For more informations, see the flyer below: </p>
					<img src="harris222.png" alt="Application image"/>

			<p> To get your application started, please fill in the form below. </p>

					<form>
			`	`		<label for="name">Name:</label>
						<input type="text" id="Name" name="name" required> <br><br>

						<label for="email">Email:</label>
						<input type="email" id="Email" name="email" required> <br><br>

						<input type="submit" value="submit">
					</form>
			</div>
			<footer>
				<p>&copy; 2025 HMB and TJY Scholarship consultants. All rights reserved. </P>
			</footer>

			<script src="js/scripts.js"> </script>
		</body>
</html>
