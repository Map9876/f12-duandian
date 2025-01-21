# f12-duandian
f12断点测试
https://github.com/copilot/c/93a78d0f-6bdc-4490-92ef-f1da9899fd10

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Display Numbers with JavaScript</title>
    <style>
        .number {
            font-size: 24px;
            margin: 10px 0;
        }
    </style>
</head>
<body>
    <h1>Display Numbers with JavaScript</h1>
    <div id="number1" class="number"></div>
    <div id="number2" class="number"></div>
    <div id="number3" class="number"></div>

    <script src="./script.js"></script>
</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Display Numbers with JavaScript</title>
    <style>
        .number {
            font-size: 24px;
            margin: 10px 0;
        }
    </style>
</head>
<body>
    <h1>Display Numbers with JavaScript</h1>
    <div id="number1" class="number"></div>
    <div id="number2" class="number"></div>
    <div id="number3" class="number"></div>

    <script src="script.js"></script>
</body>
</html>
JavaScript文件（script.js）
JavaScript
￼
// Display number 1
document.getElementById('number1').innerText = '1';

// Display number 2
document.getElementById('number2').innerText = '2';

// Display number 3
document.getElementById('number3').innerText = '3';
解释：
HTML文件（index.html）：

包含了基本的HTML结构和CSS样式。
包含三个div元素，分别用于显示数字1、2、3，这些div具有不同的id（number1、number2、number3）。
在body的底部包含了一个<script>标签，用于引用外部的JavaScript文件（script.js）。
JavaScript文件（script.js）：

使用document.getElementById方法获取每个div元素，并设置其innerText属性为相应的数字1、2、3。
如何使用：
创建两个文件，一个名为index.html，另一个名为script.js。
将HTML代码复制到index.html文件中。
将JavaScript代码复制到script.js文件中。
使用浏览器打开index.html文件，即可看到三个位置
