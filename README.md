alert-beautifier
================

Beautifies window.alert

## How to Use

Just include `beautiful-alert.css` and `beautiful-alert.js` and execute `$.initBeautifulAlert();`. Edit `beautiful-alert.css` to customize the style to fit your needs.

```html
<!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" type="text/css" href="beautiful-alert.css" />
    <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.8.1/jquery.min.js"></script>
    <script type="text/javascript" src="beautiful-alert.js"></script>
    <script type="text/javascript">
        $(document).ready(function () {
            $.initBeautifulAlert();
        });
    </script>
</head>
<body>
    <button onclick="window.alert('This is a test message.'); " class="open-dialog">Test window.alert</button>
</body>
</html>
```
