
<h2 align="center">World-First-Website-Clone</h2>
<hr>

Hello there,

I am **Harsh Vardhan Pandey**. Welcome to **World-First-Website-Clone**

This repository contains clone of the world's first website, usihg HTML.

I would like to **thank you** for your time if you are going through this text right now.

<a href="https://worldfirstwebsite.netlify.app/" target="_blank">Visit World's First Website</a>
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.button {
  border-radius: 4px;
  background-color: #f4511e;
  border: none;
  color: #FFFFFF;
  text-align: center;
  font-size: 28px;
  padding: 20px;
  width: 200px;
  transition: all 0.5s;
  cursor: pointer;
  margin: 5px;
}

.button span {
  cursor: pointer;
  display: inline-block;
  position: relative;
  transition: 0.5s;
}

.button span:after {
  content: '\00bb';
  position: absolute;
  opacity: 0;
  top: 0;
  right: -20px;
  transition: 0.5s;
}

.button:hover span {
  padding-right: 25px;
}

.button:hover span:after {
  opacity: 1;
  right: 0;
}
</style>
</head>
<body>

<h2>Animated Button</h2>

<a href="https://worldfirstwebsite.netlify.app/"<button class="button"><span>Visit World's First Website</span></button></a>

</body>
</html>


Thanks,<br/>
Harsh Vardhan Pandey
