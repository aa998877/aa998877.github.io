<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <title></title>
    <meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <style>
        * {
            margin: 0;
            padding: 0;
            border: 0;
            position: absolute;
            width: 100%;
            height: 100%;
        }
    </style>
</head>
<body>

<iframe id="iframe" scrolling="auto" src=''></iframe>

<script>
    // 获取url参数
    function getQueryVariable(variable) {
        var query = window.location.search.substring(1);
        var vars = query.split("&");
        for (var i=0;i<vars.length;i++) {
            var pair = vars[i].split("=");
            if (pair[0] == variable) {return pair[1];}
        }
        return(false);
    }

    // 解密字符串
    var decode = function(string, key) {
        try{
            string = atob(string.replace(/\$/ig,'/').replace(/@/ig,'+').replace(/-/ig,'='));
            var len = key.length;
            var code = '';
            for (var i = 0, k; i < string.length; i++) {
                k = i % len;
                code += String.fromCharCode(string.charCodeAt(i) ^ key.charCodeAt(k));
            }
            code =  atob(code);
            if (code && code.indexOf('%') !== -1) {
                code = decodeURIComponent(code);
            }
            return code;
        } catch(e) {
            return '';
        }
    };

    // 解析参数
    var k = getQueryVariable("k");
    var t = getQueryVariable("t");
    var u = getQueryVariable("u");
    if (t) {
        document.title = decode(t, k);
    }
    if (u) {
        document.getElementById("iframe").src = decode(u, k);
    }
</script>

</body>
</html>
