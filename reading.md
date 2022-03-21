# Reading javascript
## 読み込み方法は３つ

１|２|３
headタグに記述|外部ファイルを読み込み|bodyタグに記述

<html>
  <head>
  <meta charset="utf-8" />
  <title>javascriptの読み込み</title>
  <!-- 1 headタグに記述 -->
  <script type="text/javascript">
    window.alert("Hello World!");
  </script>
  <!--------------------->
  </head>
  
  <body>
  <!-- 2 外部ファイルを読み込み-->
  <script type="text/javascript" src="hello_ex.js"></script>
  <!------------------------->
    <p>
    　Javascriptの読み込み方法は３種類あります。
    </p>
  <!-- 3 bodyタグに記述 ※閉じタグの直前-->
  <script type="text/javascript">
    window.alert("Hello World!");
  </script>
  <!--------------------------------->
  </body> 

</html>
