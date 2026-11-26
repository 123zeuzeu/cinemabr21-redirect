# cinemabr21-redirect

<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Cinema BR21</title>
<style>
body {
  background: #101014;
  color: white;
  font-family: Arial, sans-serif;
  text-align: center;
  padding: 60px 20px;
}
a {
  display: inline-block;
  background: white;
  color: black;
  padding: 16px 25px;
  border-radius: 10px;
  text-decoration: none;
  font-weight: bold;
}
</style>
</head>
<body>

<h1>Cinema BR21</h1>
<p>Redirecionando para o site...</p>

<a id="abrir" href="https://cinemabr21.megaembed.com">
ABRIR CINEMA BR21
</a>

<script>
const destino = "https://cinemabr21.megaembed.com";
const android = /Android/i.test(navigator.userAgent);

if (android) {
  document.getElementById("abrir").href =
    "intent://cinemabr21.megaembed.com/#Intent;scheme=https;action=android.intent.action.VIEW;category=android.intent.category.BROWSABLE;end";
}

setTimeout(() => {
  if (!/Instagram/i.test(navigator.userAgent)) {
    window.location.href = destino;
  }
}, 1800);
</script>

</body>
</html>
