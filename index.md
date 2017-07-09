---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
---
<html lang="en" class="no-js">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">

	<link href='http://fonts.googleapis.com/css?family=PT+Sans:400,700' rel='stylesheet' type='text/css'>
	<link href="css/bootstrap.min.css" rel="stylesheet">
	<link rel="stylesheet" href="css/reset.css"> <!-- CSS reset -->
	<link rel="stylesheet" href="css/style.css"> <!-- Resource style -->
	
	<script src="js/modernizr.js"></script> <!-- Modernizr -->

	<link rel="prefetch" href="img/girl.gif" />
	<link rel="prefetch" href="img/guy.gif" />
	<link rel="prefetch" href="img/robot.gif" />
	<link rel="prefetch" href="img/item1.jpg" />
	<link rel="prefetch" href="img/item2.jpg" />
	<link rel="prefetch" href="img/item3.jpg" />
	<link rel="prefetch" href="img/item4.jpg" />
  	
	<title>Лаборатория робототехники и трехмерной печати</title>
</head>
<body>

	
	{% include header.html %} 

	{% include navigation.html %} 	

	<!-- <main class="cd-content"> -->
		<!-- your content here -->
		<div class="container">
		<div class="row main">
			<div class="col-md-6 vertical-center">
					<div class="main-text">
					<h3>Создаем будущее вместе</h3>
					<h1>Лаборатория робототехники и трехмерной печати</h1>
				
					<p>
					Наша лаборатория создана на базе <a href="http://isuct.ru" target="_blank">Ивановского Государственного Химико-Технологического университета</a> и предоставляет возможность школьникам и студентам освоить такие направления как робототехника, трехмерная печать и программирование.
					</p>
					<div class="btn-block">
						<button class="m-btn-left">Записаться на занятие</button>
						<button class="m-btn-right">Посмотреть проекты</button>
					</div>
					</div>
			</div>
  			<div class="col-md-6 vertical-center">
  				<div class="animation" ><img id="gif" src="img/girl.gif"></div>
  				
  			</div>
  			</div>
  		</div>
		
		
			
	<!-- </main>  --><!-- cd-content -->


	{% include footer.html %}

</body>