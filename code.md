# Code

Here is an example of some coding I learned through Mizzou's Intro to Information Technology class. If you want to learn more visit [Mizzou's Information Technology Page](https://engineering.missouri.edu/academics/it/).

---

```html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Fizz Buzz</title>
<script>

function fizzbuzz() {
	var display = document.getElementById('display');
	var displayHTML = "";
	for (i = 0; i < 100; i++) {
		displayHTML += "<p>" + i + "</p>";
	}
	display.innerHTML = displayHTML;
}

</script>

</head>

<body onload="fizzbuzz()">
<div id="display">

</div>
</body>

</html>
```



[Return to Homepage](./aboutme.md)



