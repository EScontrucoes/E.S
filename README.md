<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>E.S CONTRUÇÃO&#x2705 </title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
     <link rel="shortcut icon" href="favicon.ico" type="image/x-icon">
    <!-- Adicione estilos personalizados aqui -->
  

  

    <style>
        /* Estilos personalizados */
        .video-section {
            text-align: center;
            margin-top: 20px;
        }
        .video-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-top: 20px;
        }
        .video-container video {
            width: 48%; /* Distribui igualmente o espaço para cada vídeo */
        }
    </style>
</head>
<body>

    <!-- Barra de Navegação -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <a class="navbar-brand" href="#">Empresa de Construção</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item active">
                    <a class="nav-link" href="#">Página Inicial</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Sobre</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Serviços</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Contato</a>
                </li>
            </ul>
        </div>
    </nav>

    <!-- Conteúdo da Página -->
    <div class="container">
        <h1>Bem-vindo à E.S CONTRUÇÃO</h1>
        <p>Oferecemos uma ampla gama de serviços de construção para atender às suas necessidades. Entre em contato conosco para obter mais informações. <a href="https://wa.me/qr/UEWAIZKBTCXLB1">WHATSAPP</a></p>
        <a href="https://wa.me/qr/UEWAIZKBTCXLB1">WHATSAPP</a>>
        
        <!-- Imagem de cabeçalho -->
        <img src="imagens/pedriro com muro.jpg" alt="imagem de uma casa " class="img-fluid">

        <!-- Frase "Entre em contato" -->
        <div class="video-section">
            <h2>Entre em contato </h2><a>href="https://wa.me/qr/UEWAIZKBTCXLB1">whats</a></div>
        <!-- Vídeos -->
        <div class="video-container">
            <video controls>
                <source src="" type="video/mp4">
                Seu navegador não suporta o elemento de vídeo.
            </video>
            <video controls>
                <source src="" type="video/mp4">
                Seu navegador não suporta o elemento de vídeo.
            </video>
        </div>

        <!-- Seção de Serviços -->
        <h2>Nossos Serviços</h2>
        <div class="row">
            <div class="col-md-4">
                <h3>Serviço 1</h3>
                <p>malhação total pra cima </p>
                    <img src="imagens/pedriro com muro.jpg" alt="">
                    Seu navegador não suporta o elemento de vídeo.

            </div>
            <div class="col-md-4">
                <h3>ljdljasklfjkalsjkflaskjflasjlfkjasl</h3>
                <p>super abdominal</p>
            </div>
            <div class="col-md-4">
                <h3>Serviço 3</h3>
                <p>Descrição do Serviço 3.</p>
            </div>
        </div>



        <!-- Depoimentos de Clientes -->
        <h2>Depoimentos</h2>
        <div class="row">
            <div class="col-md-6">
                <blockquote>
                    <p>"Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante."</p>
                    <footer>Cliente 1</footer>
                </blockquote>
            </div>
            <div class="col-md-6">
                <blockquote>
                    <p>"Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante."</p>
                    <footer>Cliente 2</footer>
                </blockquote>
            </div>
        </div>

        <!-- Formulário de Contato -->
        <h2>Contate-nos</h2>
        <form action="processar_formulario.php" method="post">
            <div class="form-group">
                <label for="nome">Nome:</label>
                <input type="text" class="form-control" id="nome" name="nome" required>
            </div>
            <div class="form-group">
                <label for="email">Email:</label>
                <input type="email" class="form-control" id="email" name="email" required>
            </div>
            <div class="form-group">
                <label for="mensagem">Mensagem:</label>
                <textarea class="form-control" id="mensagem" name="mensagem" rows="5" required></textarea>
            </div>
            <button type="submit" class="btn btn-primary">Enviar</button>
        </form>
    </div>

    <!-- Rodapé -->
    <footer class="footer bg-dark">
        <div class="container">
            <div class="row">
                <div class="col-md-6">
                    <h5>Contato</h5>
                    <ul>
                        <li>Endereço: Av. Exemplo, 123 - Bairro, Cidade</li>
                        <li>Telefone: (XX) XXXX-XXXX</li>
                        <li>Email: contato@empresa.com</li>
                    </ul>
                </div>
                <div class="col-md-6">
                    <h5>Redes Sociais</h5>
                    <ul class="list-unstyled">
                        <li><a href="#">Facebook</a></li>
                        <li><a href="#">Twitter</a></li>
                        <li><a href="#">Instagram</a></li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>

    <!-- Scripts do Bootstrap -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
