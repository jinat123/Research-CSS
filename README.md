<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Activity 44 - Research CSS</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: pink;
            line-height: 1.6;
        }
        .header {
            padding: 20px;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            background-color: blueviolet;
        }
        .header h1 {
            color: pink;
            margin: 0;
            font-family: papyrus,serif;
        }
        .webpage h1 {
            font-family: "Times New Roman",serif;
            text-align: center;
            font-size: 50px;
        }
        .text-example {
            margin: 20px;
            padding: 10px;
            background-color: white;
            border: 1px solid pink;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: black;
            color: pink;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Activity 44: Research CSS</h1>
    </div>
    <div class="webpage">
        <h1>First Webpage</h1>
    </div>
    <h3>Text Styling Examples</h3>
    <div class="text-example">
        <h5>Example 1: Font Size and Color</h5>
        <p style="color: blue;">This is an example of changing color.</p>
        <p style="font-size: 20px;">This is an example of changing the font-size.</p>
    </div>
    <div class="text-example">
        <h5>Example 2: Font Weight</h5>
        <p style="font-weight: normal;">This text has normal font weight.</p>
        <p style="font-weight: bold;">This text is bold due to the font weight property.</p>
    </div>
    <div class="text-example">
        <h5>Example 3: Text Alignment</h5>
        <p style="text-align: left;">This text is left-aligned using the text alignment property.</p>
        <p style="text-align: center;">This text is centered using the text alignment property.</p>
        <p style="text-align: right;">This text is right-aligned using the text alignment property.</p>
    </div>
    <h3>Box Model Example</h3>
    <div class="box-model">
        <div style="border: 1px solid black; margin: 3em; padding: 50px; width: fit-content;">
            This is an example of the box model. The black border surrounds the content area with 50px of padding.
        </div>
        <div style="border: 1px solid deepskyblue; margin: 50px; width: fit-content;">
            This is an example of the box model. The blue border surrounds the content area with 50px of margin.
        </div>
        <div style="border: 1px solid black; margin: 3em;">
            This is another example of the box model. The black border surrounds the content area with 3em of margin.
        </div>
        <div style="border: 1px solid #da1010; margin: 3em; padding: 50px; width: fit-content;">
            This is an example of the box model. The red border surrounds the content area with 50px of padding.
        </div>
    </div>
    <h3>Background</h3>
    <div style="background-color: lightblue; border: 1px solid black; padding: 10px; width: 15em;">
        Box with Lightblue Background
    </div>
    <div style="background-color: blue; border: 1px solid black; padding: 10px; color: white; width: 15em;">
        Box with Blue Background
    </div>
    <div style="background-color: lightblue; border: 1px solid black; padding: 10px; width: 15em;">
        Box with Lightblue Background
    </div>
    <footer>
        <p>&copy; 2024 Jinelyn B. Mangubat All rights reserved.</p>
    </footer>
</body>
</html>
