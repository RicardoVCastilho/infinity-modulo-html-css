# Atividades de CSS Grid

## Atividade 01: Layout Básico com CSS Grid

### Enunciado:
Crie um layout básico usando **CSS Grid** com três áreas: cabeçalho, conteúdo principal e rodapé.

- O cabeçalho deve ocupar toda a largura na parte superior.
- O conteúdo principal deve ocupar o centro da página.
- O rodapé deve estar fixo na parte inferior da página, ocupando toda a largura.

### Requisitos:
- Use `display: grid` no contêiner principal.
- Defina três linhas para a grade usando `grid-template-rows`.
- Atribua o cabeçalho, conteúdo principal e rodapé às suas respectivas áreas.

### Objetivo:
Criar uma página simples com cabeçalho, conteúdo principal e rodapé usando **CSS Grid**.

---

## Atividade 02: Galeria de Imagens com CSS Grid

### Enunciado:
Crie uma galeria de 6 imagens dispostas em um layout de grade (**grid**) usando **CSS Grid**.

### Requisitos:
- Utilize `display: grid` no contêiner `grid-gallery`.
- Defina o layout da grade com 3 colunas de largura igual, onde as imagens se ajustam automaticamente.
- Aplique espaçamento entre as colunas e linhas da grade usando a propriedade `gap`.
- Defina uma borda ou sombra ao redor das imagens para destacar cada item da galeria.
- Adicione um efeito de hover nas imagens para interatividade, como um leve aumento no tamanho ou uma mudança de opacidade.

### Objetivo:
Criar uma galeria de 6 imagens dispostas em um layout de grade (grid) usando **CSS Grid**, mantendo a simplicidade e organização do layout sem utilizar media queries.

# Atividades - Pseudo-elementos em CSS

## 📝 Atividade 03

**Descrição:**  
Crie um parágrafo simples com algum texto.

**Instruções:**  
- Use o pseudo-elemento `::before` para adicionar o texto **"Início:"** antes do conteúdo do parágrafo.  
- Use o pseudo-elemento `::after` para adicionar o texto **"Fim."** após o conteúdo do parágrafo.  
- Estilize os textos adicionados com **cor** e **margem** para destacá-los do conteúdo original.

**Requisitos:**
- Utilize a propriedade `content` para inserir o texto nos pseudo-elementos.
- Aplique estilos como `color`, `margin`, entre outros, para diferenciar o conteúdo gerado.

**Objetivo:**  
Praticar a utilização dos pseudo-elementos para adicionar conteúdo visual **antes** e **depois** de um elemento HTML.

---

## 📝 Atividade 04

**Descrição:**  
Crie um parágrafo com várias linhas de texto.

**Instruções:**  
- Use o pseudo-elemento `::first-letter` para **aumentar o tamanho da primeira letra** e aplicar uma **cor diferente**.  
- Use o pseudo-elemento `::first-line` para aplicar estilos exclusivos à **primeira linha**, como **mudança de cor** e **tipo de fonte**.  
- Estilize o parágrafo para torná-lo visualmente agradável.

**Requisitos:**
- Aplique estilos como `font-size`, `color` e `font-weight` para personalizar a **primeira letra**.
- Utilize estilos como `color` e `font-style` para a **primeira linha** do parágrafo.

**Objetivo:**  
Utilizar pseudo-elementos para aplicar estilos específicos à **primeira letra** e à **primeira linha** de um parágrafo.

# 🧪 Atividades 05 e 06 — Media Queries

## 📱 Atividade 05

**Descrição:**

Crie uma página HTML e siga os passos abaixo:

- Adicione um parágrafo de texto e um botão.
- Utilize **media queries** para alterar:
  - O tamanho da fonte do parágrafo
  - A cor do botão  
  em dispositivos com largura de tela **menor que 600px**.

### 🎯 Objetivo:
Praticar a aplicação de **media queries** para ajustar o layout em **dispositivos móveis**.

---

## 💻 Atividade 06

**Descrição:**

Crie uma página HTML e siga os passos abaixo:

- Adicione:
  - Um **cabeçalho**
  - Um **menu de navegação**
  - Um **conteúdo principal**
  - Um **rodapé**

- Utilize **media queries** para ajustar o layout em **três breakpoints diferentes**:

  - **Dispositivos móveis:** `max-width: 600px`
  - **Tablets:** `min-width: 601px` e `max-width: 1024px`
  - **Desktops:** `min-width: 1025px`

### 🎯 Objetivo:
Criar um **layout responsivo** que se adapta a diferentes tamanhos de tela usando **media queries**.

