<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Galeria de Mídia</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css"> <!-- Link do Font Awesome -->
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
            background-color: #0d3624; /* Cor de fundo cinza claro */
        }
        h1 {
            color: #333;
            margin-top: 20px;
        }
        /* Estilo para a galeria usando CSS Grid */
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr)); /* Cria colunas automáticas */
            gap: 15px; /* Espaçamento entre as imagens e vídeos */
            padding: 20px;
            max-width: 1200px;
            margin: 0 auto; /* Centraliza a galeria */
            background-color: rgba(255, 255, 255, 0.7); /* Fundo branco semitransparente */
            border-radius: 10px; /* Arredondando os cantos da galeria */
        }
        .gallery img, .gallery video {
            width: 100%; /* Faz com que as imagens e vídeos ocupem toda a largura da célula */
            height: auto;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        /* Estilo para o botão flutuante */
        .whatsapp-button {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background-color: #25D366; /* Cor do WhatsApp */
            color: white;
            border: none;
            border-radius: 50%; /* Mantendo o botão redondo */
            padding: 20px;
            width: 70px; /* Definindo uma largura fixa */
            height: 70px; /* Definindo uma altura fixa */
            display: flex;
            justify-content: center;
            align-items: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
            cursor: pointer;
            z-index: 1000;
        }
        .whatsapp-button:hover {
            background-color: #128C7E;
        }
        .whatsapp-button i {
            font-size: 30px; /* Tamanho maior para o ícone */
        }
    </style>
</head>
<body>
    <h1>Minha Galeria de Mídia</h1>
    <div class="gallery">
        <img src="C:\Users\alan1\OneDrive\Imagens\FOTOGRAFIAS\PRINCIPE DAS ALIANÇAS\ALIANÇAS SOLITARIAS/Cancun (1).jpg" alt="ALIANÇAS">
        <video controls autoplay muted>
            <source src="video.mp4" type="video/mp4">
            Seu navegador não suporta vídeos.
        </video>
        <video controls autoplay muted>
            <source src="1.mp4" type="video/mp4">
            Seu navegador não suporta vídeos.
        </video>
    </div>

    <!-- Botão flutuante do WhatsApp com o ícone -->
    <a href="https://wa.me/SEUNUMERODETELEFONE" target="_blank">
        <button class="whatsapp-button">
            <i class="fab fa-whatsapp"></i> <!-- Ícone do WhatsApp -->
        </button>
    </a>
</body>
</html>
