# Projeto Montego Palace

Bem-vindo ao projeto Montego Palace, um site fictício de hotel desenvolvido em HTML e CSS. Este documento visa fornecer informações abrangentes sobre o projeto, incluindo sua estrutura, funcionalidades e dependências.

## Visão Geral

O Montego Palace é um site fictício projetado para oferecer informações detalhadas sobre o hotel, suas acomodações, experiências gastronômicas e opções de contato. O design elegante e atraente visa cativar os visitantes e transmitir a qualidade e o requinte do hotel.

## Estrutura do Projeto

O projeto é estruturado em três principais arquivos:

1. *index.html*: Este arquivo contém a estrutura HTML do site, incluindo a definição da página, metadados, links para folhas de estilo e o conteúdo principal da página.

2. *df.html*: Este arquivo contém a estrutura HTML da segunda página do site.

3. *styles.css*: Este arquivo contém os estilos CSS que controlam o layout e a aparência do site.

## Funcionalidades

### Barra de Navegação

O site possui uma barra de navegação no cabeçalho que permite aos usuários navegar facilmente pelas diferentes seções do site, incluindo "O HOTEL", "ACOMODAÇÕES", "GASTRONOMIA" e "CONTATO". Os links são clicáveis e direcionam o usuário para a seção correspondente.

### Parte Inicial

A seção inicial apresenta uma imagem de fundo atraente do hotel e um título principal que chama a atenção dos visitantes. Há também uma breve descrição convidando os visitantes a celebrar momentos especiais no Montego Palace.

### Acomodações

Esta seção apresenta informações detalhadas sobre diferentes tipos de acomodações oferecidas pelo hotel. Cada tipo de quarto é apresentado em um cartão separado, com uma imagem, descrição e preço. Os visitantes podem visualizar as opções disponíveis e seus detalhes.

### Gastronomia

A seção de gastronomia destaca os restaurantes e bares do hotel. Cada um é apresentado com uma imagem e descrição.

### Contato

Nesta seção, os visitantes podem encontrar informações de contato do hotel, incluindo endereço, e-mail, telefone e WhatsApp. Essas informações permitem que os visitantes entrem em contato com o hotel facilmente.

## Estilos CSS

O arquivo `styles.css` contém estilos CSS que são aplicados ao site para torná-lo atraente. Alguns dos estilos notáveis incluem:

- Estilos para o cabeçalho, barra de navegação e rodapé.
- Estilos para os cartões de acomodação e restaurante.
- Estilos para as imagens exibidas no site.
- Estilos para títulos e parágrafos.

## Requisitos e Dependências

Para executar este projeto, você precisa de um navegador da web moderno que suporte HTML e CSS. Não há dependências externas, pois o projeto utiliza apenas tecnologias front-end padrão.

## Instruções de Instalação

Não é necessário instalar nada para executar o projeto. Basta abrir o arquivo `index.html` em um navegador da web.

## Como Usar

- Abra o arquivo `index.html` em um navegador para visualizar o site.
- Use a barra de navegação para explorar as diferentes seções.
- Explore as informações sobre Dúvidas Frequentes clicando no botão fixado na tela no canto inferior direito.

## Autoria e Créditos

- Autor: Larissa Coutinho
- Imagens: Pexels, iStock e outros bancos de imagens.
  

## Tags, Seletores e Classes Usados e Suas Funções

### HTML da Primeira Página

- `<!DOCTYPE html>`: Define o tipo de documento como HTML5.
- `<html>`: Define o elemento raiz que engloba todo o conteúdo HTML do documento.
- `<head>`: Contém informações sobre o documento, como metadados, títulos e links para folhas de estilo.
- `<meta charset="UTF-8">`: Define a codificação de caracteres como UTF-8, permitindo que caracteres especiais sejam exibidos corretamente.
- `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Configura a escala inicial da viewport para dispositivos móveis.
- `<link rel="shortcut icon" href="favicon.ico" type="image/x-icon">`: Especifica o ícone da página, exibido na guia do navegador.
- `<title>`: Define o título da página exibido na barra de título do navegador.
- `<link rel="stylesheet" type="text/css" href="styles.css">`: Liga o arquivo de estilo externo styles.css à página.
- `<style>`: Define estilos diretamente no documento HTML, neste caso, importando uma fonte do Google Fonts.
- `<body>`: Contém todo o conteúdo visível da página.
- `<a>`: Cria links para outras páginas ou recursos.
- `<header>`: Define o cabeçalho da página.
- `<nav id="barradenavegacao">`: Define uma barra de navegação.
- `<ul>`: Cria uma lista não ordenada na barra de navegação.
- `<li>`: Cria itens de lista na barra de navegação.
- `<div id="inicial">`: Define uma seção inicial da página.
- `<h1>`: Título principal da seção inicial.
- `<p>`: Parágrafo na seção inicial.
- `<div id="reservas">`: Define uma seção para reservas.
- `<form>`: Cria um formulário para entrada de dados.
- `<input type="date" name="Data">`: Cria um campo de entrada de data no formulário.
- `<input type="submit" value="checar disponibilidade">`: Cria um botão de envio no formulário.
- `<div id="ohotel">`: Define uma seção sobre o hotel.
- `<h3>`: Título da seção sobre o hotel.
- `<img src="img/fachadahoteljpg.jpg" alt="Frente do Hotel">`: Exibe uma imagem com uma descrição.
- `<div class="paragrafos">`: Define uma div para parágrafos na seção sobre o hotel.
- `<p>`: Parágrafo na seção sobre o hotel.
- `<div id="acomodacoes">`: Define uma seção sobre as acomodações do hotel.
- `<h3>`: Título da seção sobre as acomodações.
- `<div class="acomodacao">`: Define uma acomodação individual no hotel.
- `<h4>`: Título da acomodação.
- `<div class="image">`: Define uma div para a imagem da acomodação.
- `<div class="description">`: Define uma div para a descrição da acomodação.
- `<p>`: Parágrafo na descrição da acomodação.
- `<em>`: Texto enfatizado em itálico na descrição da acomodação.
- `<section id="contato">`: Define uma seção de contato.
- `<div class="content">`: Define o conteúdo da seção de contato.
- `<h3>`: Título da seção de contato.
- `<p>`: Parágrafos com informações de contato.
- `<address>`: Define um endereço de contato.
- `<a href="mailto:contato@montegopalace.com.br">`: Cria um link de e-mail.
- `<a href="tel: +1234567890">`: Cria links de telefone e WhatsApp.
- `<footer>`: Define o rodapé da página.

### HTML da Segunda Página

- `<div idd="titulodf">`: Esta tag `<div>` é usada para criar uma divisão ou seção na página e possui um atributo `idd` com o valor "titulodf".
- `<h1>`: Esta tag `<h1>` é usada para criar um cabeçalho de nível 1, indicando o título principal da página.
- `<p>`: Esta tag `<p>` é usada para criar parágrafos de texto.
- `<br>`: Esta tag `<br>` é usada para criar uma quebra de linha.
- `<ol>`: Esta tag `<ol>` é usada para criar uma lista.
- `<li>`: Esta tag `<li>` é usada para criar itens de lista dentro de uma lista. 
- `<strong>`: Esta tag `<strong>` é usada para enfatizar o texto, tornando-o em negrito.

### CSS
- `box-sizing: border-box;`: Define a modelagem da caixa para o padrão "border-box".
- `margin: 0;`: Remove margens padrão de todos os elementos.
- `padding: 0;`: Remove preenchimentos padrão de todos os elementos.
- `.botaofixo`: Define o estilo para um botão de posição fixa no canto inferior direito da página.
- `.linha-superior, .linha-inferior`: Define o estilo para linhas superior e inferior.
- `body`: Define o estilo geral do corpo da página, como a fonte, cor de fundo e cor do texto.
- `.container`: Define o estilo para um contêiner com largura máxima e margens automáticas.
- `header`: Define o estilo para o cabeçalho da página, incluindo a cor de fundo e a borda inferior.
- `header ul`: Define o estilo para a lista não ordenada no cabeçalho.
- `header ul li`: Define o estilo para os itens da lista no cabeçalho.
- `header a`: Define o estilo para os links no cabeçalho, incluindo a cor e a transição de cor.
- `#inicial`: Define o estilo para a seção inicial da página, incluindo a imagem de fundo e estilos de texto.
- `#reservas`: Define o estilo para a seção de reservas, incluindo a cor de fundo e estilos para inputs e botões.
- `.acomodacoes`: Define o estilo para uma grade de acomodações.
- `.acomodacao`: Define o estilo para cada acomodação, incluindo caixa, imagem e efeitos de hover.
- `.acomodacao h4` e `.acomodacao p`: Define o estilo para títulos e parágrafos dentro das acomodações.
- `#ohotel img`: Define o estilo para as imagens na seção do hotel.
- `#ohotel h3, #acomodacoes h3, #gastronomia h3, #contato h3`: Define o estilo para os títulos nas seções da página.
- `#gastronomia h4`: Define o estilo para os títulos da seção de gastronomia.
- `#ohotel p, #gastronomia p, #contato p`: Define o estilo para parágrafos nas seções da página.
- `#ohotel, #gastronomia, #contato, img`: Define o estilo para imagens e seus contêineres.
- `#gastronomia img`: Define o estilo para imagens na seção de gastronomia.
- `footer`: Define o estilo para o rodapé da página.
- `address`:  Define o estilo para o elemento de endereço no rodapé.
- `#titulodf`, `#p1`, `#p2`, `ol`, `li`, `li strong`: Define o estilo específico para elementos na página "df.html", como cabeçalho, parágrafos, listas e itens de lista.
   


Agradeço por explorar o projeto Montego Palace e espero que tenha uma experiência agradável!
