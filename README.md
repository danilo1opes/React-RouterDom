# Ranek - Loja Virtual

## 📋 Descrição do Projeto
O Ranek é uma aplicação de loja virtual desenvolvida em React como parte do curso da Origamid. O projeto apesar de ter uma visualização simples ele implementa um catálogo de produtos com páginas de navegação, detalhes de produto e página de contato, utilizando React Router e consumindo uma API externa.

## 🚀 Tecnologias Utilizadas
- **React** - Biblioteca JavaScript para construção de interfaces
- **React Router Dom** - Sistema de roteamento para React
- **CSS Modules** - Estilização com escopo local
- **Fetch API** - Para consumo da API externa
- **React Hooks** - useState e useEffect para gerenciamento de estado

## 🔍 Funcionalidades
- Listagem de produtos na página inicial
- Navegação entre páginas com rotas
- Visualização detalhada de cada produto
- Página de contato
- Animações de transição entre páginas
- Componente de carregamento durante requisições
- Gestão dinâmica de títulos de página (SEO)

# 📁 Estrutura do Projeto

## 🧩 Componentes

### App.js
Componente principal que configura o roteamento usando React Router, incluindo:
- Rotas para produtos, detalhes de produto e contato
- Layout com cabeçalho e rodapé fixos

### Produtos.js
Exibe a listagem de produtos na página inicial:
- Consome a API para buscar todos os produtos
- Renderiza os produtos com imagem e nome
- Links para páginas de detalhes

### Produto.js
Página de detalhes do produto:
- Consome a API para buscar informações detalhadas do produto
- Exibe imagens, nome, preço e descrição
- Tratamento de estados de carregamento e erro
- SEO otimizado para cada produto

### Head.js
Componente para gerenciamento de SEO:
- Define dinamicamente o título e descrição da página

### Header.js e Footer.js
Componentes de layout que são mantidos em todas as páginas.

## 📊 Estados e Efeitos
O projeto utiliza React Hooks para gerenciamento de estado:
- **useState**: Para armazenar dados de produtos e estados de carregamento
- **useEffect**: Para realizar requisições à API e sincronizar dados
- **useParams**: Para capturar parâmetros da URL

## 🌐 API
O projeto consome a API da Origamid:
- Endpoint principal: `https://ranekapi.origamid.dev/json/api/produto`
- Endpoint de produto: `https://ranekapi.origamid.dev/json/api/produto/{id}`

## 📝 Lições Aprendidas
- Implementação de rotas com React Router
- Consumo de APIs com Fetch
- Gerenciamento de estados com React Hooks
- Criação de interfaces responsivas
- Componentização eficiente
- Tratamento de erros e estados de loading

Projeto desenvolvido como parte do curso de React da Origamid.
