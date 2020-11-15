### Card-with-Html-and-Css
#### Enjoy coding with html and css...

លំហាត់ខាងក្រោមនេះ ទាមទារឲ្យអ្នកមានចំណេះដឹងទាក់ទងនឹង:
- HTML
- CSS
  - Position
  - Flexbox
 
# លំហាត់ Card
![Thumbnail](/images/1.jpg)
# កូដ HTML:
```javascript
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="utf-8">
	<title>Card</title>
	<!-- Css -->
	<link rel="stylesheet" type="text/css" href="css/style2.css">
	<!-- Google Font -->
	<link rel="preconnect" href="https://fonts.gstatic.com">
	<link href="https://fonts.googleapis.com/css2?family=Ubuntu:wght@300&display=swap" rel="stylesheet">
	<link rel="preconnect" href="https://fonts.gstatic.com">
	<link href="https://fonts.googleapis.com/css2?family=Preahvihear&family=Ubuntu:wght@300&display=swap" rel="stylesheet">
	<link rel="preconnect" href="https://fonts.gstatic.com">
	<link href="https://fonts.googleapis.com/css2?family=Content&family=Preahvihear&family=Ubuntu:wght@300&display=swap" rel="stylesheet">
</head>
<body>
	<div class="card">
		<div class="image">
			<img src="images/vannda.jpg" alt="vannda">
		</div>
		<div class="content">
			<h1 class="title">
				<span class="eng">Vann Da</span> - <span class="kh-title">វណ្ណដា</span>
			</h1>
			<p class="paragraph kh">
				ខ្ញុំចាំពេលមួយកាលនៅរៀនហើយប្រឡងធ្លាក់មួយថ្នាក់គ្រូខ្ញុំប្រាប់ថា”បរាជ័យជាបទពិសោធន៍” ពេលនោះខ្ញុំរៀបកាតាបដើរចេញពីថ្នាក់ទាំងដែលគេមើលមុខខ្ញុំគ្រប់គ្នា ហើយខ្ញុំបានស្រែកប្រាប់គាត់ថា “បើសិនជាបរាជ័យរាល់ថ្ងៃនេះនៅតែជាបទពិសោធន៍ពិតមែន ខ្ញុំគ្មានថ្ងៃជោគជ័យទេ ព្រោះបើខ្ញុំរវល់តែធ្វើតាមបទពិសោធន៍នៃភាពបរាជ័យ ថ្ងៃណាទើបខ្ញុំជោគជ័យ?? ពាក្យស្លោកបរាជ័យជាបទពិសោធន៍គឺគ្មានន័យសម្រាប់ខ្ញុំទេ អ្វីដែលខ្ញុំយល់ត្រូវគឺ បរាជ័យត្រូវតែខ្លាំងជាងបទពិសោធន៍”៕
			</p>
		</div>
	</div>
</body>
</html>
```
# កូដ CSS:
```javascript
body{
	margin: 0;
	padding: 0;
	height: 100vh;
	display: flex;
	justify-content: center;
	align-items: center;
	background-color: #212F3D;
}

.eng{
	font-family: 'Ubuntu', sans-serif;
}

.kh-title{
	font-family: 'Preahvihear', cursive;
}

.kh{
	font-family: 'Content', cursive;
}

.card{
	/*background-color: red;*/
	width: 400px;
	display: flex;
	flex-direction: column;
	align-items: center;
	position: relative;
	box-shadow: 2px 4px 20px #333;
}

.card:hover .image > img{
	top: 100%;
	left: 50%;
	transform: translate(-50%,-100%);
}

.card:hover .content{
	top: -10px;
}

.card .image > img{
	width: 100%;
	margin-bottom: -3px;
	position: absolute;
	top: 50%;
	left: 50%;
	transform: translate(-50%,-50%);
	z-index: 10;
	cursor: pointer;
	transition: all 0.3s linear;
}

.card .content{
	width: 90%;
	background-color: #34495E;
	color: #f6f6f6;
	text-align: center;
	padding: 10px 40px;
	position: absolute;
	z-index: 5;
	top: -160px;
	transition: all 0.3s linear;
	box-shadow: 2px 4px 20px #333;
}

.card .content .title{
	margin: 0;
}
```
[Facebook-MengSreang Channel](https://www.facebook.com/mengsreangchannel)

[Facebook-CodeIsMine](https://www.facebook.com/CodeIsMine)

[YouTube-MengSreang Channel](https://www.youtube.com/channel/UCE6UmKNi-bYNWwOBUYoT-yQ)

[YouTube-CodeIsMine](https://www.youtube.com/channel/UCBKsUkGih9kdXcrz54zNH1w)

### អរគុណច្រើន សំណាងល្អ!🙏
