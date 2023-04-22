# online-test-application
DESCRIPTION
The Online Test Application system creates an application that enables users to provide online tests, review them, and display the results.
System Details
This system contains three main modules: Quiz, Review, and Result. The quiz section of the online test application accepts the questions in JSON format. The JSON file can be easily shared from the server in the pre-defined format. The application renders the test at the client-side.
The “Review and display result” section allows users to declare the results immediately. You can simply call another JSON with the answers in it and evaluate and display the results immediately.
Source Code:
Index:
<!DOCTYPE html>
	<html lang="en">
	<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Online Test Application</title>
	<link rel="stylesheet" href="style.css"/>

	</head>
	<body>
	
	<div class="container">
	<div class="leftSide">
	<img src="https://d1ymz67w5raq8g.cloudfront.net/Pictures/480xany/6/5/5/509655_shutterstock_1506580442_769367.jpg"alt="quiz logo"class="tilt">

	</div>
	<div class="rightSide"><br>
	<h1>Welcome to Online Test Application</h1><br>
	<ul style="list-style-type:circle">
	
	<li><b>Frontend Quiz</b></li>
	<li><b>Consist of 5 questions</b></li>
	</ul>
	<a href="questions.html">Start Quiz</a>

	
	</div>
	</div>
	</body>
	<script src="js/jquery-3.5.1.min.js"></script>

	<script src="quiz.js"></script>

	<script src="script.js"></script>

	</html>

