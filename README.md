<!DOCTYPE html>
<html lang="pt-br">
	<head>
		<meta charset="UTF-8">
		<title>Barbearia do Pedro</title>
		<link rel="stylesheet" href="style-home.css">
	</head>

	<body>
		<header>
			<h1 class="titulo-principal">Barbearia do Pedro</h1>
		</header>
		<img id="banner" src="banner.jpg">
		<div class="principal">
			<h2 class="titulo-centralizado">Sobre a Barbearia do Pedro</h2>
	 
			<p>Localizada no coração da cidade a <strong>Barbearia do Pedro</strong> traz para o mercado o que há de melhor para o seu cabelo e barba. Fundada em 2019, a Barbearia Alura já é destaque na cidade e conquista novos clientes a cada dia.</p>

			<p id="missao"><em>Nossa missão é: <strong>"Proporcionar auto-estima e qualidade de vida aos clientes"</strong>.</em></p>

			<p>Oferecemos profissionais experientes e antenados às mudanças no mundo da moda. O atendimento possui padrão de excelência e agilidade, garantindo qualidade e satisfação dos nossos clientes.</p>
		</div>

		<div class="beneficios">
			<h3 class="titulo-centralizado">Benefícios</h3>

			<ul>
				<li class="itens">Atendimento aos Clientes</li>
				<li class="itens">Espaço diferenciado</li>
				<li class="itens">Localização</li>
				<li class="itens">Profissionais Qualificados</li>
			</ul>

			<img src="beneficios.jpg" class="imagembeneficios">
		</div>
	</body>
</html>



header {
	background: #BBBBBB;
	padding: 20px 0;
}

.caixa {
	position: relative;
	width: 940px;
	margin: 0 auto;
}

nav {
	position: absolute;
	top: 110px;
	right: 0;
}

nav li {
	display: inline;
	margin: 0 0 0 15px;
}

nav a {
	text-transform: uppercase;
	color: #000000;
	font-weight: bold;
	font-size: 22px;
	text-decoration: none;
}

nav a:hover {
	color: #C78C19;
	text-decoration: underline;
}

.produtos {
	width: 940px;
	margin: 0 auto;
	padding: 50px 0;
}

.produtos li {
	display: inline-block;
	text-align: center;
	width: 30%;
	vertical-align: top;
	margin: 0 1.5%;
	padding: 30px 20px;
	box-sizing: border-box;
	border: 2px solid #000000;
	border-radius: 10px;
}

.produtos li:hover {
	border-color: #C78C19;
}

.produtos li:active {
	border-color: #088C19;	
}

.produtos li:hover h2 {
	font-size: 34px;
}

.produtos h2 {
	font-size: 30px;
	font-weight: bold;
}

.produto-descricao {
	font-size: 18px;
}

.produto-preco {
	font-size: 22px;
	font-weight: bold;
	margin-top: 10px;
}

footer {
	text-align: center;
	background: url("bg.jpg");
	padding: 40px 0;
}

.copyright {
	color: #FFFFFF;
	font-size: 13px;
	margin: 20px 0 0;
}

main {
	width: 940px;
	margin: 0 auto;
}

form {
	margin: 40px 0;
}

form label, form legend {
	display:block;
	font-size: 20px;
	margin: 0 0 10px;
}

.input-padrao {
	display: block;
	margin: 0 0 20px;
	padding: 10px 25px;
	width: 50%;
}

.checkbox {
	margin: 20px 0;
}

.enviar {
	width:40%;
	padding: 15px 0;
	background: orange;
	color: white;
	font-weight: bold;
	font-size: 18px;
	border: none;
	border-radius: 5px;
	transition: 1s all;
	cursor: pointer;
}

.enviar:hover {
	background: darkorange;
	transform: scale(1.2);
}

table {
	margin: 20px 0 40px;
}

thead {
	background: #555555;
	color: white;
	font-weight: bold;
}

td, th {
	border: 1px solid #000000;
	padding: 8px 15px;
}
