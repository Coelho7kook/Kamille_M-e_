echo "# Kamille_M-e_" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Coelho7kook/Kamille_M-e_.git
git push -u origin main



<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Feliz Aniversário, Mãe!</title>
    <style>
        body {
            background-image: url('background1.jpg');
            background-size: cover;
            font-family: 'Arial', sans-serif;
            color: #333;
            text-align: center;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .content {
            background-color: rgba(255, 255, 255, 0.7); /* Transparência leve para legibilidade */
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            max-width: 600px;
            width: 90%;
        }

        h1 {
            color: #FF69B4;
            font-size: 2.5em;
            margin-bottom: 15px;
        }

        p {
            font-size: 1.2em;
            color: #555;
            line-height: 1.5;
        }

        footer {
            margin-top: 20px;
            font-size: 0.9em;
            color: #888;
        }

        .buttons {
            margin-top: 20px;
        }

        .btn {
            padding: 10px 20px;
            background-color: rgba(255, 105, 180, 0.7); /* Transparência nos botões */
            color: white;
            border: none;
            border-radius: 10px;
            cursor: pointer;
            font-size: 1em;
            margin: 0 5px;
            transition: background-color 0.3s;
        }

        .btn:hover {
            background-color: rgba(255, 105, 180, 1); /* Cor mais intensa ao passar o mouse */
        }
    </style>
    <script>
        function changeBackground(image) {
            document.body.style.backgroundImage = `url(${image})`;
        }
    </script>
</head>
<body>
    <audio autoplay loop>
        <source src="musica.mp3" type="audio/mpeg">
        Seu navegador não suporta o elemento de áudio.
    </audio>

    <div class="content">
        <h1>Feliz Aniversário, Mãe!</h1>
        <p>Mãe, hoje é um dia especial, mas, na verdade, todos os dias em que tenho você ao meu lado são especiais. Você é mais do que minha mãe, é meu porto seguro, a pessoa que sempre esteve comigo, me protegendo, me guiando, e me amando de uma forma tão única e incomparável.</p>

        <p>Desde que eu era pequena, você sempre me mostrou o que é o amor de verdade, aquele amor que não espera nada em troca, que simplesmente dá e se entrega. Nos seus olhos, sempre vi o cuidado, e nas suas palavras, sempre encontrei conforto, mesmo nas horas mais difíceis. Não sei como seria minha vida sem você. Sua presença é a luz que ilumina cada canto da minha alma, tornando tudo mais bonito e mais seguro.</p>

        <p>Você me ensinou tanto, e não só com palavras, mas com seu exemplo. Cada gesto, cada sacrifício, tudo o que você fez por mim é o que me molda e me faz ser quem eu sou hoje. Sua força é algo que admiro todos os dias, uma força silenciosa, que sabe exatamente o momento de ser firme, mas que nunca deixa de ser carinhosa. Mãe, você é um exemplo de amor, de bondade, de coragem.</p>

        <p>Neste seu aniversário, eu queria te dar o mundo inteiro, mas sei que o que mais te faz feliz é simplesmente estar cercada pelas pessoas que você ama. Então, eu te dou meu amor, minha gratidão e meu compromisso de sempre ser a filha que você merece, aquela que vai te encher de orgulho e te recompensar, mesmo que seja apenas um pouco, por tudo o que você fez e continua fazendo por mim.</p>

        <p>Eu te amo, mãe, com todo o meu coração, e sei que, não importa quantas vezes eu diga isso, nunca será suficiente para expressar o quanto você significa para mim. Que este novo ano da sua vida seja cheio de alegrias, de paz e de tudo aquilo que te faz sorrir, porque você merece o mundo, e muito mais. Feliz aniversário!</p>

        <footer>Com todo o amor do mundo, sua filha, Kamille</footer>

        <!-- Botões para trocar o plano de fundo -->
        <div class="buttons">
            <button class="btn" onclick="changeBackground('background1.jpg')">Imagem 1</button>
            <button class="btn" onclick="changeBackground('background2.jpg')">Imagem 2</button>
            <button class="btn" onclick="changeBackground('background3.jpg')">Imagem 3</button>
            <button class="btn" onclick="changeBackground('background4.jpg')">Imagem 4</button>
            <button class="btn" onclick="changeBackground('background5.jpg')">Imagem 5</button>
        </div>
    </div>
</body>
</html>
