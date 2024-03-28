<!DOCTYPE html>
<html lang="en">
<head>
	<title>Структура HTML страницы</title>
	<link rel="preconnect" href="https://fonts.googleapis.com">
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
	<link href="https://fonts.googleapis.com/css2?family=Anonymous+Pro:ital,wght@0,400;0,700;1,400;1,700&family=PT+Mono&display=swap" rel="stylesheet">
	<style type="text/css">
	* {
		font-family: "Anonymous Pro";
		margin: 10px;
		}
	p, h1, h2, h3, button {
		padding-left: 10%;
		padding-right: 10%;
		padding-top: 15px;
		padding-bottom: 10px;
	}
	p {
		font-size: 20px;
		line-height: 32px;
		padding-bottom: 10px;
		margin: -5px;
	}
	h1 {
		font-size: 50px;
	}
	img {
		margin-left: 130px;
		border: 5px solid;
		border-color: #42474f;
	}
	.color{
		color:#f1256f
	}
	span {
		margin-left: -3px;
		margin-right:-3px;
	}
	button {
		padding: .75rem 1.25rem;
		border-radius: 7px;
		background-color: #FFA0B8;
		border: none;
		font-size: 1rem;
	}
	a {
		text-decoration: none;
		color: black;
	}
	.button1 {
		margin-left: -5px;
	}
	</style>
</head>
<body>
	<h1>Структура HTML страницы</h1>
	<p>Страница сайта - это текстовый файл с <span class="color">расширением .html</span>. Этот файл обязательно должен иметь тег <span class="color">&#60;html&#62;</span>, внутри него должны быть теги <span class="color">&#60;head&#62;</span> для служебного содержимого страницы и <span class="color">&#60;body&#62;</span> для основного текста, который будет отобржаться на экранне. Перед  тегом <span class="color">&#60;html&#62;</span> пишется конструкция doctype, она указывает версию языка HTML, на которой сделан сайт. Сейчас это выглядит так- <span class="color">&#60;!DOCTYPE html&#62;</span>.
	</p>
	<p><span class="color">Код</span> выглядит так:</p>
	<img 
	src="C:\Users\Аделина\OneDrive\Desktop\проект\img\код со структурой HTML страницы.png"
	height="250px" 
	width="600px" 
	>
	<p>
		<button class="button1"><a href="Учебник HTML.html">Вернуться на главную страницу</a></button>
		<button><a href="Абзацы.htmll">Перейти к следующему уроку</a></button>
	</p>
</body>
</html> 
