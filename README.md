Você pode criar um coração romântico em HTML usando o elemento "span" e estilizando com CSS. Aqui está um exemplo básico:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Coração Romântico</title>
  <style>
    .coracao {
      color: red;
      font-size: 24px;
      position: relative;
      display: inline-block;
    }

    .coracao::before,
    .coracao::after {
      content: '♥';
      position: absolute;
      top: 0;
      transform: translateY(-50%);
    }

    .coracao::before {
      left: -10px;
    }

    .coracao::after {
      left: 10px;
    }
  </style>
</head>
<body>
  <p>Para minha querida <span class="coracao"></span></p>
</body>
</html>
```

Este código cria um par de corações ao redor do caractere "♥". Você pode ajustar o tamanho, a cor e o posicionamento conforme preferir. Basta copiar e colar este código em um arquivo HTML e abrir no seu navegador para ver o resultado.
