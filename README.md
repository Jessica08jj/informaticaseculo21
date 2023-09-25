<!DOCTYPE html>
<html>
<head>
    <title>Informática no Século 21</title>
    <style>
        /* Estilo para o título que muda de cor e tem pontos de interrogação animados */
        h1 {
            animation: changeColor 5s infinite alternate, blink 1s infinite; /* Animação que altera a cor e faz os pontos de interrogação piscarem */
            border: 2px solid #ecc19c; /* Adicionando uma borda laranja de 2 pixels ao redor do título */
            padding: 20px; /* Adicionando um espaço interno de 20 pixels entre o texto e a borda */
            background-color: #ffecf2; /* Cor de fundo rosa bebê */
            border-radius: 15px; /* Borda arredondada */
            width: 80%; /* Largura do "smartphone" */
            margin: auto; /* Centraliza o título na página */
            text-align: center; /* Alinha o texto no centro */
            font-family: 'Lobster', cursive; /* Fonte elegante do Google Fonts */
            font-size: 36px; /* Tamanho da fonte */
            color: #1e847f; /* Cor do texto dentro do "smartphone" */
            position: relative; /* Permite posicionar os pontos de interrogação relativamente ao título */
            display: inline-block; /* Permite que a borda se ajuste ao conteúdo do título */
        }

        @keyframes changeColor {
            0% { color: #ecc19c; }
            25% { color: #1e847f; }
            50% { color: #000000; }
            75% { color: #ecc19c; }
            100% { color: #1e847f; }
        }

        @keyframes blink {
            0%, 100% { content: "??"; } /* Mostra os pontos de interrogação */
            50% { content: ""; } /* Esconde os pontos de interrogação */
        }

        /* Estilo para o conteúdo */
        .content {
            max-width: 800px; /* Largura máxima para o conteúdo */
            margin: 20px auto; /* Margem para centralizar o conteúdo */
            text-align: justify; /* Justificar o texto */
            font-size: 18px; /* Tamanho da fonte para o conteúdo */
            color: #000000; /* Cor do texto */
        }

        /* Estilo para o subtítulo */
        h2 {
            color: #ecc19c; /* Cor laranja */
            font-family: 'Arial', sans-serif; /* Fonte padrão */
            font-size: 24px; /* Tamanho da fonte para o subtítulo */
        }

        /* Estilo para a lista */
        ul {
            color: #000000; /* Cor preta */
            list-style-type: disc; /* Estilo de marcador de lista */
        }

        /* Estilo para os itens da lista */
        li {
            margin-bottom: 10px; /* Espaço entre os itens da lista */
        }

        /* Estilo para o fundo rosa bebê */
        body {
            background-color: #ffecf2; /* Cor de fundo rosa bebê */
            font-family: 'Arial', sans-serif; /* Fonte padrão para o corpo */
        }

        /* Estilo para a imagem dentro do título */
        h1 img {
            vertical-align: middle; /* Alinha verticalmente a imagem ao texto */
            margin-right: 10px; /* Espaçamento à direita da imagem */
        }
    </style>
    <link href="https://fonts.googleapis.com/css2?family=Lobster&display=swap" rel="stylesheet"> <!-- Importa a fonte Lobster do Google Fonts -->
</head>
<body>
    <h1><img src="https://cdn5.colorir.com/desenhos/color/201636/um-computador-portatil-a-casa-o-quarto-1293730.jpg" alt="Computador" height="40">Informática no Século 21</h1>

    <div class="content">
        <p>
            A informática no século 21 desempenha um papel fundamental em nossa sociedade moderna.
            A revolução digital transformou a forma como interagimos, aprendemos, trabalhamos e nos comunicamos.
            Suas vantagens são inúmeras e impactam vários aspectos de nossas vidas diárias.
        </p>

        <h2>Vantagens da Informática:</h2>

        <ul>
            <li><strong>Maior Conectividade:</strong> A internet e as redes sociais nos permitem conectar-se com pessoas ao redor do mundo, facilitando a comunicação e colaboração.</li>
            <li><strong>Acesso à Informação:</strong> Com a informática, temos acesso fácil e rápido a uma vasta quantidade de informações, o que contribui para o aprendizado e o desenvolvimento pessoal.</li>
            <li><strong>Automatização de Tarefas:</strong> A automação de processos torna as tarefas mais eficientes e libera tempo para atividades mais estratégicas e criativas.</li>
            <li><strong>Inovação e Avanço Tecnológico:</
