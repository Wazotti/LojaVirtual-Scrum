# 🌌 Star Void – Loja Virtual de Streetwear

### 👩‍💻 Desenvolvido por:  
• Maria Clara Mazotti  
*(Projeto individual)*

---

## 💻 Tecnologias Utilizadas

- **Front-end:** HTML, Tailwind CSS, JavaScript  
- **Back-end:** *Não utilizado*  
- **Banco de dados:** *Não utilizado (dados mockados via array de objetos JS)*  

---

## 📝 Descrição do Projeto

A **Star Void** é uma loja virtual de streetwear, focada na venda de tênis, bonés e roupas. O sistema simula um ambiente real de compras com funcionalidades como:

- Catálogo dinâmico de produtos  
- Filtro por categorias  
- Barra de pesquisa  
- Carrinho de compras  
- Finalização de pedido com controle de estoque

Os dados dos produtos foram simulados com arrays em JavaScript e são renderizados dinamicamente no front-end.

---

## 🚀 Funcionalidades

- Renderização dinâmica dos produtos  
- Filtro por categoria  
- Pesquisa com animação  
- Modal de imagem ampliada  
- Carrinho funcional com contador  
- Finalização da compra com validação  
- Reset automático do carrinho  
- Layout 100% responsivo  
- Separação de arquivos JavaScript  

---

## 🧠 Metodologia Ágil

- A organização do projeto foi feita com **Metodologia Ágil**, dividida em **20 sprints** com entregas incrementais e testes contínuos.
- Um **quadro Kanban** foi utilizado para visualização e acompanhamento das tarefas.

---

## 📊 Kanban do Projeto

| 📌 To Do                                     | 🚧 In Progress              | ✅ Done                    |
| :-------------------------------------------| :-------------------------- | :------------------------- |
| 🔒 Implementar autenticação                  | 🖼️ Página de produto único | 🧱 Estrutura HTML completa |
| 🧑‍💼 Criar painel administrativo             | 💳 Checkout                 | 🔍 Filtro de produtos      |
| 🧪 Testes automatizados                      |                             | 🛒 Carrinho funcional       |
| 🗂️ Simulação de dados com array de objetos (mock) |                             | 🔗 API REST (GET/POST)     |
|                                              |                             | 🚀 Deploy no GitHub Pages  |
|                                              |                             | 📘 README completo          |

---

## 📅 Planejamento de Sprints

<details>
  <summary><strong>✅ Sprint 1 – Estrutura HTML base</strong></summary>

- **O que foi feito:** Criada a estrutura do `index.html` com os elementos básicos do site e links para scripts.  
- **Desenvolvedor:** Maria Clara  
- **Período de desenvolvimento:** 1 dia  
- **Período de testes:** 1 dia  
- **Período de revisão:** 1 dia  
- **Período de deploy:** 1 dia  
- **Data:** 01/08/2025 – 02/08/2025  

</details>

<details>
  <summary><strong>✅ Sprint 2 – Criação do array de produtos (mock)</strong></summary>

- **O que foi feito:** Criado array `produtos[]` com objetos contendo nome, valor, categoria, imagem e estoque.  
- **Desenvolvedor:** Maria Clara  
- **Período de desenvolvimento:** 1 dia  
- **Período de testes:** 1 dia  
- **Período de revisão:** 1 dia  
- **Período de deploy:** 1 dia  
- **Data:** 03/08/2025 – 04/08/2025  

</details>

<details>
  <summary><strong>✅ Sprint 3 – Renderização dinâmica dos produtos</strong></summary>

- **O que foi feito:** Função `renderizarProdutos()` criada para exibir os produtos dinamicamente com base no array.  
- **Desenvolvedor:** Maria Clara  
- **Período de desenvolvimento:** 1 dia  
- **Período de testes:** 1 dia  
- **Período de revisão:** 1 dia  
- **Período de deploy:** 1 dia  
- **Data:** 05/08/2025 – 06/08/2025  

</details>

<details>
  <summary><strong>✅ Sprint 4 – Estilização com Tailwind CSS</strong></summary>

- **O que foi feito:** Aplicação do Tailwind nos cards de produto, header, botões e responsividade básica.  
- **Desenvolvedor:** Maria Clara  
- **Período de desenvolvimento:** 1 dia  
- **Período de testes:** 1 dia  
- **Período de revisão:** 1 dia  
- **Período de deploy:** 1 dia  
- **Data:** 07/08/2025 – 08/08/2025  

</details>

<details>
  <summary><strong>✅ Sprint 5 – Criação do filtro por categoria</strong></summary>

- **O que foi feito:** Botões de categoria que filtram os produtos com a função `filtrarCategoria()`.  
- **Desenvolvedor:** Maria Clara  
- **Período de desenvolvimento:** 1 dia  
- **Período de testes:** 1 dia  
- **Período de revisão:** 1 dia  
- **Período de deploy:** 1 dia  
- **Data:** 09/08/2025 – 10/08/2025  

</details>

<details>
  <summary><strong>✅ Sprint 6 – Implementação da barra de pesquisa animada</strong></summary>

- **O que foi feito:** Criado botão que exibe/esconde o campo de busca com transição visual.  
- **Desenvolvedor:** Maria Clara  
- **Período de desenvolvimento:** 1 dia  
- **Período de testes:** 1 dia  
- **Período de revisão:** 1 dia  
- **Período de deploy:** 1 dia  
- **Data:** 11/08/2025 – 12/08/2025  

</details>

<details>
  <summary><strong>✅ Sprint 7 – Função de pesquisa por nome</strong></summary>

- **O que foi feito:** Implementada função `pesquisarProduto()` com normalização e atualização dinâmica.  
- **Desenvolvedor:** Maria Clara  
- **Período de desenvolvimento:** 1 dia  
- **Período de testes:** 1 dia  
- **Período de revisão:** 1 dia  
- **Período de deploy:** 1 dia  
- **Data:** 13/08/2025 – 14/08/2025  

</details>

<details>
  <summary><strong>✅ Sprint 8 – Criação e exibição do carrinho</strong></summary>

- **O que foi feito:** Criado `aside` fixo que exibe os itens do carrinho com botão de fechar.  
- **Desenvolvedor:** Maria Clara  
- **Período de desenvolvimento:** 1 dia  
- **Período de testes:** 1 dia  
- **Período de revisão:** 1 dia  
- **Período de deploy:** 1 dia  
- **Data:** 15/08/2025 – 16/08/2025  

</details>

<details>
  <summary><strong>✅ Sprint 9 – Adicionar ao carrinho com controle de estoque</strong></summary>

- **O que foi feito:** Implementada função `adicionarAoCarrinho(id)` com controle de quantidade e estoque.  
- **Desenvolvedor:** Maria Clara  
- **Período de desenvolvimento:** 1 dia  
- **Período de testes:** 1 dia  
- **Período de revisão:** 1 dia  
- **Período de deploy:** 1 dia  
- **Data:** 17/08/2025 – 18/08/2025  

</details>

<details>
  <summary><strong>✅ Sprint 10 – Contador de itens no carrinho</strong></summary>

- **O que foi feito:** Ícone no topo com contador atualizado a cada adição.  
- **Desenvolvedor:** Maria Clara  
- **Período de desenvolvimento:** 1 dia  
- **Período de testes:** 1 dia  
- **Período de revisão:** 1 dia  
- **Período de deploy:** 1 dia  
- **Data:** 19/08/2025 – 20/08/2025  

</details>

<details>
  <summary><strong>✅ Sprint 11 – Finalização da compra com validação de estoque</strong></summary>

- **O que foi feito:** Validação do estoque antes da compra e decremento do mesmo após finalização.  
- **Desenvolvedor:** Maria Clara  
- **Período de desenvolvimento:** 1 dia  
- **Período de testes:** 1 dia  
- **Período de revisão:** 1 dia  
- **Período de deploy:** 1 dia  
- **Data:** 21/08/2025 – 22/08/2025  

</details>

<details>
  <summary><strong>✅ Sprint 12 – Modal para visualização da imagem ampliada</strong></summary>

- **O que foi feito:** Criado modal com fundo escuro que exibe imagem ampliada ao clicar.  
- **Desenvolvedor:** Maria Clara  
- **Período de desenvolvimento:** 1 dia  
- **Período de testes:** 1 dia  
- **Período de revisão:** 1 dia  
- **Período de deploy:** 1 dia  
- **Data:** 23/08/2025 – 24/08/2025  

</details>

<details>
  <summary><strong>✅ Sprint 13 – Animações de hover e interações visuais</strong></summary>

- **O que foi feito:** Animações de escala e hover em botões e produtos com Tailwind.  
- **Desenvolvedor:** Maria Clara  
- **Período de desenvolvimento:** 1 dia  
- **Período de testes:** 1 dia  
- **Período de revisão:** 1 dia  
- **Período de deploy:** 1 dia  
- **Data:** 25/08/2025 – 26/08/2025  

</details>

<details>
  <summary><strong>✅ Sprint 14 – Responsividade com grid Tailwind</strong></summary>

- **O que foi feito:** Layout adaptado com grid responsivo usando `grid-cols` para celular, tablet e desktop.  
- **Desenvolvedor:** Maria Clara  
- **Período de desenvolvimento:** 1 dia  
- **Período de testes:** 1 dia  
- **Período de revisão:** 1 dia  
- **Período de deploy:** 1 dia  
- **Data:** 27/08/2025 – 28/08/2025  

</details>

<details>
  <summary><strong>✅ Sprint 15 – Função toggle de pesquisa com animação</strong></summary>

- **O que foi feito:** Alternância entre mostrar e ocultar o campo de busca.  
- **Desenvolvedor:** Maria Clara  
- **Período de desenvolvimento:** 1 dia  
- **Período de testes:** 1 dia  
- **Período de revisão:** 1 dia  
- **Período de deploy:** 1 dia  
- **Data:** 29/08/2025 – 30/08/2025  

</details>

<details>
  <summary><strong>✅ Sprint 16 – Separação de arquivos JavaScript</strong></summary>

- **O que foi feito:** Organização do código JS em arquivos separados por função (`main.js`, `categorias.js`).  
- **Desenvolvedor:** Maria Clara  
- **Período de desenvolvimento:** 1 dia  
- **Período de testes:** 1 dia  
- **Período de revisão:** 1 dia  
- **Período de deploy:** 1 dia  
- **Data:** 31/08/2025 – 01/09/2025  

</details>

<details>
  <summary><strong>✅ Sprint 17 – Estrutura e exibição do aside do carrinho</strong></summary>

- **O que foi feito:** Carrinho com rolagem e exibição dos itens com nome e valor total.  
- **Desenvolvedor:** Maria Clara  
- **Período de desenvolvimento:** 1 dia  
- **Período de testes:** 1 dia  
- **Período de revisão:** 1 dia  
- **Período de deploy:** 1 dia  
- **Data:** 02/09/2025 – 03/09/2025  

</details>

<details>
  <summary><strong>✅ Sprint 18 – Função de reset do carrinho após compra</strong></summary>

- **O que foi feito:** Esvaziamento do array `carrinho[]` e atualização visual.  
- **Desenvolvedor:** Maria Clara  
- **Período de desenvolvimento:** 1 dia  
- **Período de testes:** 1 dia  
- **Período de revisão:** 1 dia  
- **Período de deploy:** 1 dia  
- **Data:** 04/09/2025 – 05/09/2025  

</details>

<details>
  <summary><strong>✅ Sprint 19 – Função mostrarTodosProdutos()</strong></summary>

- **O que foi feito:** Botão que renderiza todos os produtos novamente.  
- **Desenvolvedor:** Maria Clara  
- **Período de desenvolvimento:** 1 dia  
- **Período de testes:** 1 dia  
- **Período de revisão:** 1 dia  
- **Período de deploy:** 1 dia  
- **Data:** 06/09/2025 – 07/09/2025  

</details>

<details>
  <summary><strong>✅ Sprint 20 – Testes e ajustes finais</strong></summary>

- **O que foi feito:** Testes de funcionalidade e ajustes de margin, espaçamentos e responsividade.  
- **Desenvolvedor:** Maria Clara  
- **Período de desenvolvimento:** 1 dia  
- **Período de testes:** 1 dia  
- **Período de revisão:** 1 dia  
- **Período de deploy:** 1 dia  
- **Data:** 08/09/2025 – 09/09/2025  

</details>

### 👩‍💻 O que foi implementado por Maria Clara

Todo o desenvolvimento do front-end, lógica em JavaScript, estrutura HTML, estilização com Tailwind, funcionalidade de carrinho, simulação de banco com arrays mockados, filtros, pesquisa, responsividade e organização em sprints foi feito por Maria Clara Mazotti, de forma individual.

---

## ✅ Vantagens da Metodologia

- Melhor controle das tarefas e prazos  
- Organização e clareza nas etapas  
- Facilidade de adaptação para ajustes  

---

## ⚠️ Desafios Encontrados

- Definir a divisão exata de tarefas no início  
- Manter um ritmo equilibrado entre as sprints  
- Simular back-end e banco de dados apenas com JS  

---

## 🌐 Deploy

O projeto está disponível em:  
🔗 [Acesse o projeto da loja online](https://Wazotti/LojaVirtual/)

---

## 📬 Contato

Para dúvidas ou sugestões:  
claramazotti@gmail.com

---

