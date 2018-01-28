# DailyPractice.github.io
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8">
		<title>首页</title>
		<style type="text/css">
			.img{
				margin-top: 100px;
				margin-bottom: 100px;
				width: 400px;
				height: 400px;
			}
			html:hover .img{
				animation-name :img; 
				animation-delay: 500ms;
				animation-duration: 1s;	
				animation-fill-mode: forwards;
			}
			@keyframes img {
				to{
				width: 100px;
				height: 100px;
				margin-top: 0px;
				}	
			}
			.div{
				text-align: center;	
			}
			.p{
				font-family: "微软雅黑";
				font-size: 20px;
				text-shadow: 1px 1px 2px  darkgray;
			}	
			html:hover .p{
				animation-name:p;
				animation-delay: 400ms;
				animation-duration: 100ms;
				animation-fill-mode:forwards ;
				transition-timing-function: ease-out;
			}
			@keyframes  p{
				from{}
				to{
				font-size: 0px;
				text-shadow: 0px 0px 0px  white;
				}
			}
		</style>
	</head>
	<body>
		<div class="div">
			<img src="../img/6bc2837472.jpg"  class="img"/>		
			<p class="p">欢迎使用</p>
		</div>
		
	</body>
</html>
