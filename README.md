# Design of a Standard Calculator

## AIM:

To design a web application for a standard calculator.

## DESIGN STEPS:

### Step 1:
Create a new django project.


### Step 2:
Make on changes in settings and create a static folder.


### Step 3:
Write a code in index.html file .


### Step 4:
And run the server and give an url to get an output.
### Step 5:
Take a screenshot of the output and uploat it.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
```python 
<!DOCTYPE html>
<html>
    <head>
        <title>SEC Demo on Calculator</title>
        <style type="text/css">
        table{
            border: 1px solid black;
            margin-left: auto;
            margin-right: auto;
        }
        input[type="text"]{
            border: 1px solid black;
            padding: 20px 30px;
            font-size: 24px;
            font-weight: bold;
            border-radius: 2px;
        }


        input[type="button"]{
            width: 100%;
            padding: 20px 40px;
            background-color:greenyellow;
            border-radius: 2px;
        }
        </style>
    </head>
    <body>
        <form name="form1" onload="result.value=''">
            <h1 style="text-align: center;color:blue;">Simple Calculator</h1>
        <table id="calc">
            <tr>
                <td colspan="4">
                    <input type="text" id="result">
                </td>
            </tr>
            <tr>
                <td><input type="button" value="1" onclick="result.value+='1'"/></td>
                <td><input type="button" value="2" onclick="result.value+='2'"/></td>
                <td><input type="button" value="3" onclick="result.value+='3'"/></td>
                <td><input type="button" value="+" onclick="result.value+='+'"/></td>
            </tr>
            <tr>
                <td><input type="button" value="4" onclick="result.value+='4'"/></td>
                <td><input type="button" value="5" onclick="result.value+='5'"/></td>
                <td><input type="button" value="6" onclick="result.value+='6'"/></td>
                <td><input type="button" value="-" onclick="result.value+='-'"/></td>
            </tr>
            <tr>
                <td><input type="button" value="7" onclick="result.value+='7'"/></td>
                <td><input type="button" value="8" onclick="result.value+='8'"/></td>
                <td><input type="button" value="9" onclick="result.value+='9'"/></td>
                <td><input type="button" value="*" onclick="result.value+='*'"/></td>
            </tr>
            <tr>
                <td><input type="button" value="/" onclick="result.value+='/'"/></td>
                <td><input type="button" value="0" onclick="result.value+='0'"/></td>
                <td><input type="button" value="." onclick="result.value+='.'"/></td>
                <td><input type="button" value="=" onclick="result.value=eval(result.value)"/></td>
            </tr>
            <tr>
                <td colspan="4">
                    <input type="button" value="clearall" id="clear" onclick="result.value=''">
                </td>
            </tr>
        </table>
        </form>
    </body>
</html>
```
## OUTPUT:
## Addition:
![add py](https://github.com/gokul-sureshkumar/standard-calculator/assets/121148715/a4e28027-a903-48b3-870c-61783ea339e2)

## Subration:
![sub py](https://github.com/gokul-sureshkumar/standard-calculator/assets/121148715/e3e69b2f-7009-47f0-b754-d0c523b0837d)

## multiplication:
![multiple py](https://github.com/gokul-sureshkumar/standard-calculator/assets/121148715/646acb7e-e88d-4e91-a93f-37245853e9f9)

## Division:
![div py](https://github.com/gokul-sureshkumar/standard-calculator/assets/121148715/3eb0ceac-f530-460b-b9b1-4a20611c83f8)

## Modulo:
![modulo py](https://github.com/gokul-sureshkumar/standard-calculator/assets/121148715/1affe7d0-0178-496a-a5da-462cd22cf40a)

## Result:
The program for implementing simple calculator is completed.

