# 2 - Firebase Highscore App

## I. Overview

- Here we will look at posting high scores to Firebase

## II. Start code

- This code will 

**firebase-high-score.html**

```html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="utf-8" />
	<title>High Score App</title>
	<style>
	*{
		font-family: monospace;
		font-size:1.2em;
	}
	#scoreElement{
		font-size:3em;
		width:5em;
		height:2.5em;
		color:white;
		background-color:black;
		border:5px solid gray;
		text-align:center;
		padding-top: 1em;
	}
	</style>
</head>
<body>


<p id="scoreElement">0</p>
<p>Name --> <input type="text" value="MADMAX" id="nameField"></p>
<button id="clickMeButton">Click Me!</button>
<button id="saveScoreButton">Save High Score</button>

<!-- #1 - link to Firebase goes here  -->


<script type="module">

/* #2 - The rest of the Firebase setup code goes here */
	
	
	let score = 0;
	
	clickMeButton.onclick = _ => {
		score++;
		scoreElement.innerText = score;
	};
	

</script>

</body>
</html>
```

<hr><hr>

**[Previous Chapter <- Firebase Part I - Intro](firebase-1.md)**

**[Next Chapter -> Firebase Part III - High Score Viewer](firebase-3.md)**