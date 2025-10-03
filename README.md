# Projeto: Formulário de Cadastro "Nova Conta"

Este projeto é uma implementação de uma tela de cadastro de usuário simples, desenvolvida com HTML e CSS.

### **HTML (`index.html`)**

* **`<head>`:** Contém as tags padrões essenciais, o título da página e o link para o arquivo css.
* **`<div class="form-container">`:** Container que envolve toda a parte do formulário, utilizado para centralizar e aplicar o css na parte principal.
* **`<form>`:** Os elemento principal do formulário.
* **`<div class="input-group">`:** Cada par de `label` e `input` foi agrupado dentro de uma `div` com esta classe para facilitar a visualização e a organização do código.

### **CSS (`style.css`)**

1.  **Parâmetros Globais:** Primeiramente, um reset simples é aplicado para remover margens e inconsistencias que o formato padrão do navegador pode causar
2.  **Variáveis (`:root`)**: Todas as cores e fontes principais extraídas do Figma foram declaradas como variáveis CSS. Isso centraliza os estilos e facilita futuras alterações em todo o site.
3.  **Estilos do `body`**: Estilos base como a fonte principal e a cor de fundo da página são aplicados ao `body`, junto com Flexbox para centralizar o formulário na tela.
4.  **Estilos de Componentes**: Cada classe do HTML recebe seus estilos específicos. Todo o código extraído do Figma foi organizado aqui.

O Figma foi uma peça central no desenvolvimento deste projeto, utilizado em duas etapas principais: Toda a interface visual, incluindo o layout, espaçamento, tipografia e a paleta de cores, foi desenhada e no Figma antes de qualquer código ser escrito. Utilizando o Dev Mode do Figma, foi possível extrair trechos de código CSS com valores exatos para utiliza-los no arquivo css.