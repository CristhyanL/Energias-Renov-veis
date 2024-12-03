<img loading="lazy" src="https://github.com/user-attachments/assets/50a48c6b-596d-410d-9e2e-816adef37043"/>

# Engenharia Mecânica - Áreas de Atuação - Energias Renováveis

<p align="center">
<img loading="lazy" src="http://img.shields.io/static/v1?label=Importante&message=Projeto%20de%20faculdade&color=GREEN&style=for-the-badge"/>
<img loading="lazy" src="http://img.shields.io/static/v1?label=STATUS&message=Em%20desenvolvimento&color=GREEN&style=for-the-badge"/>
</p>

## Resumo
Este projeto foi criado com o intuito de servir como uma expansão visual do projeto apresentado presencialmente, para o trabalho da matéria de Introdução à Engenharia Mecânica. O trabalho consistia em conectar a engenharia mecânica com as energias renováveis e entrar em contato com um engenheiro mecânico que trabalha na área para trazer uma perspectiva aos calouros do curso. 

## Funcionalidades JavaScript
Além dos códigos básicos de **HTML** e **CSS**, também inclui o **JavaScript** com várias funcionalidades interativas, incluindo a alternância de links de navegação, fixação da barra de navegação, **rolagem suave** e um **acordeão**.

Primeiramente, a seção **"close links"** lida com a alternância de visibilidade dos links de navegação. Quando o botão de alternância é clicado, a altura do contêiner de links é ajustada para mostrar ou ocultar os links. Se a altura do contêiner for **zero**, ela é ajustada para a altura dos links; caso contrário, é definida como **zero**, ocultando os links.

Na seção **"fixed navbar"**, o código fixa a barra de navegação no topo da página quando o usuário rola para baixo. Ele seleciona a barra de navegação e um link de **"voltar ao topo"**. Um evento de rolagem é adicionado ao objeto **window**, que verifica a quantidade de rolagem vertical. Se a rolagem for maior que a altura da barra de navegação, a classe **`fixed-nav`** é adicionada à barra de navegação, fixando-a no topo. Além disso, se a rolagem for maior que **500 pixels**, a classe **`show-link`** é adicionada ao link de **"voltar ao topo"**, tornando-o visível.

A seção **"smooth scroll"** implementa a **rolagem suave** para links de navegação. O código seleciona todos os links com a classe e adiciona um evento de clique a cada um deles. Quando um link é clicado, a página rola suavemente para a seção correspondente. A posição de rolagem é calculada com base na altura da barra de navegação e do contêiner de links. Se a barra de navegação não estiver fixada, a posição é ajustada para compensar a altura da barra.

## Deploy

Para acessar o Deploy do projeto clique no link abaixo:

https://cristhyanl.github.io/Energias-Renovaveis/
