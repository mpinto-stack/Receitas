# Livro de Receitas do Miguel

Repositório do site pessoal de receitas do Miguel.

## Funcionamento do site

O site é estático e foi pensado para ser publicado com GitHub Pages. Não usa base de dados, servidor ou serviços pagos.

A base do conteúdo está no ficheiro:

```text
data/recipes.json
```

O JavaScript lê esse ficheiro e gera automaticamente:

- receitas separadas por **Entradas**, **Pratos principais** e **Sobremesas**;
- cartões de receitas;
- página de detalhe de cada receita;
- pesquisa por nome, ingrediente, categoria, tags e texto da preparação;
- filtros rápidos por tipo de receita/ingrediente;
- lista de compras por receita;
- lista de compras combinada a partir de várias receitas selecionadas;
- modo cozinhar com passos grandes para usar no telemóvel;
- página para gerar novas receitas em JSON.

## Estrutura do código

```text
.
├── index.html
├── css/
│   └── styles.css
├── js/
│   └── app.js
├── data/
│   └── recipes.json
└── assets/
    └── logo.svg
```

## Como adicionar receitas

### Método recomendado

1. Abrir o site.
2. Ir a **Adicionar receita**.
3. Preencher os campos.
4. Clicar em **Gerar JSON**.
5. Copiar o bloco gerado.
6. Abrir `data/recipes.json` no GitHub.
7. Colar o novo bloco dentro da lista de receitas.
8. Fazer commit.

### Método direto

Também é possível editar diretamente o ficheiro `data/recipes.json` no GitHub, mantendo a mesma estrutura dos objetos existentes.

## Publicação com GitHub Pages

1. Criar um repositório no GitHub.
2. Enviar todos estes ficheiros para o repositório.
3. Abrir **Settings** do repositório.
4. Entrar em **Pages**.
5. Escolher a branch principal e a pasta raiz.
6. Guardar.
7. O GitHub Pages publica o site no endereço indicado.

## Notas

- O site foi feito para funcionar bem em telemóvel e computador.
- As seleções da lista de compras ficam guardadas no browser através de `localStorage`.
- O campo `miguelin` representa a classificação pessoal de 1 a 5 estrelas Miguelin.
- O campo `photo` está preparado para uma foto futura por receita.
