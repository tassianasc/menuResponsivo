# Menu Responsivo
Este código cria um menu de navegação responsivo que se adapta a diferentes tamanhos de tela. Em telas maiores, ele exibe uma barra de navegação tradicional. Em telas menores, ele exibe um ícone de menu que, quando clicado, mostra um menu móvel.

# Descrição
# index.html
Este arquivo HTML define a estrutura básica do seu site. Aqui está o que cada parte faz:

<!DOCTYPE html>: Declara o tipo de documento como HTML5.
<html lang=“pt-br”>: Define o idioma da página como português do Brasil.
<head>: Contém metadados sobre o documento, como o conjunto de caracteres, a compatibilidade com navegadores e o link para o arquivo CSS.
<body>: Contém o conteúdo visível da página.
Dentro do <body>, temos:

<header>: Define o cabeçalho da página.
<nav class=“nav-bar”>: Cria uma barra de navegação com três seções principais:
<div class=“logo”>: Contém o logotipo do site.
<div class=“nav-list”>: Contém a lista de links de navegação.
<div class=“login-button”>: Contém o botão de login.
<div class=“mobile-menu-icon”>: Contém o ícone do menu para dispositivos móveis.
<div class=“mobile-menu”>: Define o menu que será exibido em dispositivos móveis.
  
# assets/css/style.css
Este arquivo CSS define o estilo visual do seu site. Aqui estão alguns pontos importantes:

@import url(‘https://fonts.googleapis.com/css2?family=Inter:wght@200;300;400;500&display=swap’);: Importa a fonte “Inter” do Google Fonts.
Estilos globais: Define o padding, margin e a fonte padrão para todos os elementos.
header: Define o estilo do cabeçalho, incluindo a cor de fundo e a sombra.
.nav-bar: Define o layout da barra de navegação, usando flexbox para distribuir os elementos.
.logo, .nav-list, .login-button: Define o estilo específico para cada uma dessas seções.
.mobile-menu-icon: Define o estilo do ícone do menu para dispositivos móveis.
@media screen and (max-width: 730px): Define estilos específicos para telas menores (dispositivos móveis), como esconder itens de navegação e exibir o menu móvel.

# assets/js/script.js
Este arquivo JavaScript adiciona interatividade ao seu site. Ele contém uma função:

function menuShow(): Esta função é chamada quando o botão do menu móvel é clicado. Ela alterna a classe “open” no menu móvel, exibindo ou escondendo o menu. Também altera o ícone do botão entre “menu” e “close”.
