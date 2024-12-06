<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <sytle>
      * {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background-color: #111;
  color: white;
  font-family: 'Courier New', Courier, monospace;
}

.container {
  text-align: center;
}

.typewriter {
  display: inline-block;
  font-size: 3rem;
  font-weight: bold;
  overflow: hidden;
  white-space: nowrap;
  border-right: 3px solid #fff;
  padding-right: 10px;
  animation: typing 3s steps(12) 1s forwards, blink 0.75s step-end infinite;
}

@keyframes typing {
  from {
    width: 0;
  }
  to {
    width: 12ch; /* Ajuste o número de caracteres com base no texto */
  }
}

@keyframes blink {
  50% {
    border-color: transparent;
  }
}

  </sytle>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="container">
    <h1 class="typewriter">Danilo Bezerra</h1>
  </div>
</body>
</html>


