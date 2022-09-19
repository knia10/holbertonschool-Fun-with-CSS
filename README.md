# Fun with CSS
In this project, you will experiment and implement fun layout with HTML and CSS ONLY!

Yes, no JavaScript!

Enjoy!

## TASKS
#### 0.Sprite languages
By using this HTML:
´´´
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 0- Sprite</title>

        <link href="0-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>
        <ul>
            <li>HTML<span class="icon i-html"></span></li>
            <li>CSS<span class="icon i-css"></span></li>
            <li>JavaScript<span class="icon i-js"></span></li>
        </ul>
    </body>
</html>
´´´
And this image file: [0-sprite.png](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/2/d416199ca6ecdbd0f8a3.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220919%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220919T212427Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=ed4f94294391a6834557186e403d5100eeb6bb346490882a474107220fb51873)

Create `0-styles.css` and generate this layout:
![alt](./images/sprite.png)
You are not allowed to change the image and the HTML - sprite is cool!

#### 1. Move the (under)line
By using this HTML:
´´´
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 1- Underline</title>

        <link href="1-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>
        <h2>
            Hello <a href="https://www.holbertonschool.com">Holberton!</a>
        </h2>
    </body>
</html>
´´´
Create `1-styles.css` and generate this layout:
![alt](./images/underline.gif)
You are not allowed to change the HTML

#### 2. Toggle
By using this HTML:
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 2- toggle</title>

        <link href="2-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>
        <div class="toggle">
            <input type="checkbox" name="toggle" class="toggle-cb" id="toggle-0" checked>
            <label class="toggle-label" for="toggle-0">
                <div class="toggle-inner"></div>
                <div class="toggle-switch"></div>
            </label>
        </div>
    </body>
</html>
```
Create `2-styles.css` and generate this layout where the <input> is has this custom toggle layout:
**Checked:**
![alt](./images/toggle_on.png)

**Unchecked:**
![alt](./images/toggle_off.png)
You are not allowed to change the HTML

#### 3. Menu

By using this HTML:
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 2- toggle</title>

        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
        <link href="3-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>

        <nav class="menu">
            <input type="checkbox" href="#" class="menu-open" name="menu-open" id="menu-open"/>
            <label class="menu-open-button" for="menu-open">
                <span class="menu-line menu-line-1"></span>
                <span class="menu-line menu-line-2"></span>
                <span class="menu-line menu-line-3"></span>
            </label>

            <a href="#" class="menu-item"> <i class="fa fa-area-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-bar-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-line-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-pie-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-table"></i> </a>
        </nav>

    </body>
</html>
```
Create `3-styles.css` and generate this layout/animation:
![alt](./images/menu.gif)
You are not allowed to change the HTML

By **Estefania Ruiz** 🦌 From **Holberton School** 🪐
