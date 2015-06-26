# lda-example

<!DOCTYPE html>
<html>
  <head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
    <title>LDAvis</title>
    <script src="d3.v3.js"></script>
    <script src="ldavis.js"></script>
    <link rel="stylesheet" type="text/css" href="lda.css">
  </head>

  <body>
    <!-- Do we need this? -->
    <div id="errorMsg"></div>

    <!-- Placeholder div -->
    <!-- <div id="lda" style="clear: left; background-color: #ffffff; transform: translate(0px, 50px)"></div>-->
    <div id="lda" style="clear: left; background-color: #ffffff; position: absolute; top: 60px; left: 0px"></div>
    <script>
      var vis = new LDAvis("#lda", "lda.json");
    </script>
  </body>

</html>
