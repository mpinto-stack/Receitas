# Livro de Receitas do Miguel

## Português

Repositório do site pessoal de receitas do Miguel.

### Funcionamento

O site é estático e foi pensado para GitHub Pages. Não usa base de dados, servidor ou serviços pagos.

O conteúdo das receitas está em:

```text
data/recipes.json
```

O JavaScript lê esse ficheiro e gera:

- receitas por abas: **Entradas**, **Pratos principais** e **Sobremesas**;
- pesquisa por nome, ingredientes, categoria, tags e preparação;
- filtros rápidos por tags;
- página de detalhe de cada receita;
- classificação pessoal de 1 a 5 estrelas **Miguelin**;
- lista de compras combinada sem ingredientes duplicados;
- itens comprados rasurados através de checkboxes;
- modo cozinhar com passos grandes para telemóvel;
- página para gerar novas receitas em JSON.

### Estrutura

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
    ├── logo.svg
    └── photos/
```

### Adicionar uma receita

1. Abre o site.
2. Vai a **Adicionar**.
3. Preenche os campos.
4. Clica em **Gerar JSON**.
5. Copia o bloco gerado.
6. No GitHub, abre `data/recipes.json`.
7. Clica no lápis de edição.
8. Cola o bloco dentro da lista de receitas.
9. Faz **Commit changes**.

### Adicionar fotos

1. Coloca a imagem em `assets/photos/`.
2. Usa nomes simples, sem espaços. Exemplo: `arroz-frito-camarao.jpg`.
3. Na receita, preenche o campo `photo` com:

```text
assets/photos/arroz-frito-camarao.jpg
```

### Publicar no GitHub Pages

1. Cria um repositório no GitHub.
2. Envia os ficheiros deste projeto.
3. Vai a **Settings > Pages**.
4. Escolhe a branch principal e a pasta raiz.
5. Guarda.

---

# Miguel's Recipe Book

## English

Repository for Miguel's personal recipe website.

### How it works

This is a static website designed for GitHub Pages. It does not require a database, server, or paid services.

Recipe content is stored in:

```text
data/recipes.json
```

The JavaScript reads that file and generates:

- recipe tabs: **Starters**, **Main dishes**, and **Desserts**;
- search by title, ingredients, category, tags, and preparation text;
- quick tag filters;
- recipe detail pages;
- personal 1-to-5 **Miguelin** star rating;
- combined shopping list without duplicated ingredients;
- bought items crossed out with checkboxes;
- cooking mode with large step-by-step instructions for mobile;
- a page to generate new recipes in JSON format.

### Structure

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
    ├── logo.svg
    └── photos/
```

### Add a recipe

1. Open the website.
2. Go to **Adicionar**.
3. Fill in the fields.
4. Click **Gerar JSON**.
5. Copy the generated block.
6. On GitHub, open `data/recipes.json`.
7. Click the edit pencil.
8. Paste the block inside the recipes list.
9. Click **Commit changes**.

### Add photos

1. Add the image to `assets/photos/`.
2. Use simple filenames without spaces. Example: `arroz-frito-camarao.jpg`.
3. In the recipe, set the `photo` field to:

```text
assets/photos/arroz-frito-camarao.jpg
```

### Publish with GitHub Pages

1. Create a GitHub repository.
2. Upload the project files.
3. Go to **Settings > Pages**.
4. Choose the main branch and root folder.
5. Save.
