<!DOCTYPE html>
<html>
<head>
    <title>Pixel Art Maker!</title>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Monoton">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1>Lab: Pixel Art Maker</h1>

    <h2>Choose Grid Size</h2>
    <form id="sizePicker">
        Grid Height:
        <input type="number" id="input_height" name="height" min="1" value="1">
        Grid Width:
        <input type="number" id="input_width" name="width" min="1" value="1">
        <input type="submit">
    </form>

    <h2>Pick A Color</h2>
    <input type="color" id="colorPicker">

    <h2>Design Canvas</h2>
    <table id="pixel_canvas"></table>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
    <script src="designs.js"></script>
</body>
</html>
