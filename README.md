<div align="center">
  <h1 align="center">
    Saúde na Tigela
    <br />
    <br />
    <a href="https://docusaurus.io">
      <img src="https://docusaurus.io/img/slash-introducing.svg" alt="Docusaurus">
    </a>
  </h1>
</div>

<p align="center">
  <a href="https://github.com/facebook/docusaurus/actions/workflows/tests.yml"><img src="https://github.com/facebook/docusaurus/actions/workflows/tests.yml/badge.svg" alt="GitHub Actions status"></a>
</p>

## Introduction

Saúde na Tigela é uma aplicação web desenvolvida para auxiliar donos de animais de estimação a monitorar a qualidade dos alimentos que oferecem aos seus pets. O sistema permite que os usuários façam o upload da embalagem dos alimentos (focando na lista de ingredientes) e, utilizando técnicas de reconhecimento de texto (OCR), analisa os ingredientes presentes. O objetivo é identificar possíveis componentes prejudiciais à saúde do animal, como conservantes artificiais (BHT, BHA), corantes e outros aditivos químicos, fornecendo orientações e explicações sobre seus efeitos.

A ideia principal do projeto é promover uma alimentação mais segura e saudável para os animais de estimação, ajudando seus tutores a tomarem decisões informadas com base nos ingredientes dos alimentos.



## Funcionalidades

- **Upload de imagens:** Permite que o usuário faça upload de fotos das embalagens de alimentos para animais.
- **Leitura automática de ingredientes**: Usa OCR para ler a lista de ingredientes diretamente da imagem.
- **Análise de ingredientes:** Identifica e exibe componentes que podem ser prejudiciais à saúde do animal.
- **Explicações detalhadas:** Fornece informações sobre os possíveis efeitos nocivos dos ingredientes identificados.

## Pré-requisitos

Certifique-se de que as seguintes ferramentas estão instaladas em seu ambiente de desenvolvimento:

- **Node.js (versão 14 ou superior)**

- **Angular CLI (versão mais recente):** Para instalar o Angular CLI globalmente, execute:

```bash
npm install -g @angular/cli
```

## Instalação

Siga os passos abaixo para configurar o projeto localmente:

- **Clone o repositório:**
```bash
git clone https://github.com/paolaarruee/Saude-Tigela.git
```

- **Navegue até a pasta do projeto:**
```bash
cd saude-tigela
```

- **Instale as dependências:**
```bash
npm install
```

- **Executando o projeto**
Para rodar o projeto localmente em um servidor de desenvolvimento, execute:

```bash
ng serve
```
Após a execução, abra o navegador e acesse http://localhost:4200/ para visualizar a aplicação.

- **Gerar build de produção**
Para gerar uma versão otimizada do projeto para produção, execute:

```bash
ng build
```
Os arquivos otimizados serão gerados na pasta dist/.

- **Rodando os testes**
Testes unitários
O projeto utiliza Karma e Jasmine para testes unitários. Para rodar os testes, utilize:
```bash
ng test
```
Isso executará os testes e exibirá os resultados diretamente no terminal.


