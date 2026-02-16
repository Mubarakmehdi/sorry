<!DOCTYPE html>
<html>
<head>
<title>Sorry Animation</title>
<style>
@keyframes sorryMove {
  0% {
    transform: scale(1);
    color: red;
  }
  50% {
    transform: scale(1.5);
    color: blue;
  }
  100% {
    transform: scale(1);
    color: red;
  }
}
</style>
</head>

<body style="margin:0; display:flex; justify-content:center; align-items:center; height:100vh; background:rgb(251, 165, 165);">

<h1 style="
font-size:80px;
font-family:Arial;
animation:sorryMove 2s infinite;
text-shadow:0 0 20px white;
">
</h1>

</body>
</html>
