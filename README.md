<!DOCTYPE html>
<html>
<head>
 <title>Simple Page</title>
</head>
<body>
<h1>Heading</h1>
<p>Paragraph text.</p>
<ul>
 <li>Item 1</li>
 <li>Item 2</li>
</ul>
<audio controls src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3"></audio>
<br>
<video width="200" controls src="https://www.w3schools.com/html/mov_bbb.mp4"></video>
<hr>
<h2>Calculator</h2>
<div style="background:pink;padding:10px;">
    <input id="a" type="number" value="0"> +
    <input id="b" type="number" value="0">
    <button onclick="add()">=</button>
    <p>Result: <span id="r">0</span></p>
</div>
<script>
function add() {
    let x = parseFloat(document.getElementById('a').value) || 0;
    let y = parseFloat(document.getElementById('b').value) || 0;
    document.getElementById('r').innerText = x + y;
}
</script>
</body>
</html>
