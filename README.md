# repositorio-duda

<!DOCTYPE html>
<html>
<head>
  <title>Minha Floricultura</title>
  <link rel="stylesheet" type="text/css" href="style.css">
  <link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/jquery.slick/1.8.1/slick.css"/>
  <style>
    .slick-prev,
    .slick-next {
      position: absolute;
      top: 50%;
      transform: translateY(-50%);
      z-index: 1;
    }

    .slick-prev {
      left: 10px;
    }

    .slick-next {
      right: 10px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Minha Floricultura</h1>
    <nav>
      <ul>
        <li><a href="#">Página Inicial</a></li>
        <li><a href="#">Catálogo de Produtos</a></li>
        <li><a href="#">Arranjos e Buquês</a></li>
        <li><a href="#">Serviços Adicionais</a></li>
        <li><a href="#">Sobre Nós</a></li>
        <li><a href="#">Contato</a></li>
      </ul>
    </nav>
  </header>

  <section id="banner">
    <h2>Bem-vindo à Minha Floricultura</h2>
    <p>Oferecemos as mais belas flores para todas as ocasiões</p>
  </section>

  <section id="destaques">
    <h2>Promoções Especiais</h2>
    <div class="destaque-item">
      <img src="https://cdn.awsli.com.br/600x450/1087/1087349/produto/60083683/219061c6d7.jpg" alt="Imagem 1"width="100" height="auto">
      <h3>Promoção da semana</h3>
      <p>para celebrar o matrimônio, carinho, afeto e gratidão!!S.</p>
    </div>
    <div class="destaque-item">
        <h3>Promoção 2</h3>
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRiskENNlDORW3IwqkmNSmjTovRe4QDavvgQQ&usqp=CAU" alt="Imagem 2"width="100" height="auto">
          <p>as suculentas são as preferidas entre nossos clientes!!.</p>
    </div>
  </section>

  <section id="catalogo">
  <h2>Catálogo de Produtos</h2>
  <div class="products-carousel">
    <div class="produto">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ5LnWifJUAJAWVD5pEk9DKMYnmbOdBn3nEiw&usqp=CAU" alt="Produto 1"width="100" height="auto">
      <h3>Rosa Vermelha</h3>
      <p>Uma rosa vermelha clássica, perfeita para expressar amor e paixão.</p>
      <p>Preço: $10.99</p>
    </div>
    <div class="produto">
      <h3>Lírio Branco</h3>
     <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSgVdNCwYRr1Dbv0W_Gv7fzOFXflreOJTNl1A&usqp=CAU" alt="Produto 1"width="100" height="auto">
      <p>O lírio branco simboliza pureza e inocência, ideal para ocasiões especiais.</p>
      <p>Preço: $12.99</p>
    </div>
    <div class="produto">
      <img src="https://images.tcdn.com.br/img/img_prod/799330/girassol_amarelo_alto_453_1_20200523155201.jpg" alt="Produto 3"width="100" height="auto">
      <h3>Girassol Amarelo</h3>
      <p>O girassol amarelo representa alegria e felicidade, perfeito para presentear.</p>
      <p>Preço: $9.99</p>
    </div>
    <div class="produto">
      <img src="https://static.novaflor.com.br/images/product/rs-3127-11222-0.jpg" alt="Produto 4"width="100" height="auto">
      <h3>Orquídea Rosa</h3>
      <p>A orquídea rosa transmite elegância e delicadeza, um presente sofisticado.</p>
      <p>Preço: $14.99</p>
    </div>
    
  </div>
</section>

              


CSSS
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

h1, h2, h3 {
  color: #333;
}

p {
  color: #666;
}

a {
  color: #009688;
  text-decoration: none;
}

a:hover {
  color: #00796b;
}

ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
}


header {
  background-color: #f5f5f5;
  padding: 20px;
}

h1 {
  color: #009688;
}

nav ul {
  display: flex;
}

nav ul li {
  margin-right: 20px;
}

#banner {
  background-color: #f5f5f5;
  padding: 40px;
  text-align: center;
}

#destaques {
  background-color: #fafafa;
  padding: 40px;
  text-align: center;
}

.destaque-item {
  margin-bottom: 40px;
}

#catalogo {
  background-color: #f5f5f5;
  padding: 40px;
}

.produto {
  background-color: #fff;
  border-radius: 5px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  padding: 20px;
  margin-bottom: 20px;
}

footer {
  background-color: #f5f5f5;
  padding: 20px;

  text-align: center;
}


.products-carousel {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}

.products-carousel .produto {
  flex-basis: calc(33.33% - 20px);
}

@media (max-width: 768px) {
  .products-carousel .produto {
    flex-basis: calc(50% - 20px);
  }
}

