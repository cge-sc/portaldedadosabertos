---
description: Aa configrações aqui apresentadas impactam em todo o Portal
---

# Configurações do Portal

Ao clicar no ícone de configuação (martelo ao lado nome do usuário), exibido apenas quando usuário administrador estiver logado, será apresenta a interface de configurações do Portal.

A tela apresenta três abas internas:&#x20;

* Administradores;
* Configuração; e&#x20;
* Lixo.

A aba de "Administradores" lista os usuários que são administradores do Portal de Dados Abertos.

<figure><img src="../../../.gitbook/assets/image (38).png" alt=""><figcaption><p>Configurações do Portal -  Aba Administradores</p></figcaption></figure>

Ao clicar em um dos usuários será apresentado o detalhamento deste.

A aba "Configuração" apresenta a opção de configurar coisas como:

* título do portal - texto que aparece ao colocar o mouse sobre o logotipo do portal;
* estilo - não deve ser alterado;
* lema do portal - pouco impacto;
* logotipo - símbolo ou ícone do Portal de Dados Abertos;
* texto "Sobre" - texto que é apresentado na tela Sobre;
* texto introdutório - texto apresentado na tela de início;&#x20;
* CSS do portal - estilo de design do portal; e
* estilo da página inicial - formato de exebição dos componentes da página inicial.

{% hint style="info" %}
**Cuidado:** não clique no botão "Reiniciar", todas as configurações serão perdidas.
{% endhint %}

Ao clicar na aba "Lixo" é apresentada a listagem de itens excluídos no sistema.

<figure><img src="../../../.gitbook/assets/image (39).png" alt=""><figcaption><p>Configurações do Portal - Aba Configuração</p></figcaption></figure>

O CSS customizado pode ser consultado abaixo.



```css
.html {
    background-color: #fff;
    background: #fff;
    color: #444;
    font-size: 14px;
    font-family: 'Open Sans',sans-serif;
}
.body {
    background-color: #fff;
    background: #f2f2f2;
    color: #444;
    font-size: 14px;
    font-family: 'Open Sans',sans-serif;
}
.js  {
    background: #000;
}
.p {
    background-color: #fff;
    background: #fff;
    color: #444;
    font-size: 14px;
    font-family: 'Open Sans',sans-serif;
}
.toolbar {
    background: #f2f2f2;
    color: #444;
}
.toolbar .breadcrumb a {
    background: #f2f2f2;
    color: #444;
}
[role="main"], .main {
    background: #f2f2f2;
    color: #444;
}
.hero {
    background: #f2f2f2;
}

.account-masthead {
    background-color: #fff;
    background: #fff;
    color: #000;
}
.account-masthead .account .ul .li .a  {
    color: #ccc;
}
.masthead {
    background-color: #fff;
    background: #fff;
    color: #000;
}
.masthead .nav {
    background-color: #fff;
    background: #fff;
    color: #000;
}
.masthead .ul .li .a {
    color: #ccc;
}
.masthead .nav .a{
    background-color: #fff;
    background: #fff;
    color: #ccc;
}
.masthead .navigation .nav-pills li a:hover, .masthead .navigation .nav-pills li a:focus, .masthead .navigation .nav-pills li.active a {
    background-color: #444;
    color: #ccc;
}
.masthead .nav > li > a, .masthead .nav > li > a:focus, .masthead .nav > li > a:hover, .masthead .nav > .active > a, .masthead .nav > .active > a:hover, .masthead .nav > .active > a:focus {
    color: #444;
}

.homepage {
    background: rgb(52, 101, 52);
}

.btn-primary {
    background-color: rgb(52, 101, 52);
}

.homepage .module-search .module-content {
    background-color: rgb(166,206,57);
}
.homepage .module-search .tags{
    background-color: rgb(52, 101, 52);
}

.site-footer a {
    color: #ccc;
}
.site-footer, .site-footer label, .site-footer small {
    color: #ccc;
}
.site-footer {
    background-color: #252525;
    background: #252525;
}
.module-content .featured{
   display: none;
}
```

A tela Lixo apresenta os conjuntos de dados ou recursos que foram excluídos pelos usuários do sistema, permitindo que o administrador possa recuperar esses itens até  que a exclusão permanente seja realizada, clicando no botão "Expurgar".

<figure><img src="../../../.gitbook/assets/image (40).png" alt=""><figcaption><p>Configuração do Portal - Aba Lixo</p></figcaption></figure>
