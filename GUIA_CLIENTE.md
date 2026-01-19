# GUIA DE EDIÇÃO - LANDING PAGE "A ROTA DO DÓLAR"

Olá! Este documento serve para orientá-lo sobre como atualizar os textos e imagens da sua nova Landing Page de alta conversão.

## 📁 Estrutura de Arquivos
- **index.html**: Onde está todo o conteúdo de texto e estrutura do site.
- **assets/**: Pasta onde ficam todas as imagens.
- **output.css**: Arquivo de estilo (não precisa mexer aqui).

---

## ✍️ Como Alterar os Textos

Para mudar títulos, parágrafos ou preços, você precisará abrir o arquivo `index.html` em um editor de texto (como Bloco de Notas ou VS Code).

1. **Localize o texto:** Use `Ctrl + F` para buscar a frase que deseja mudar.
2. **Edite com cuidado:** Altere apenas o texto que está **dentro** das marcações (tags).
   
   *Exemplo:*
   **Original:** `<h1>A Rota do Dólar</h1>`
   **Como editar:** `<h1>O Seu Novo Título Aqui</h1>`

   ⚠️ **Atenção:** Não apague os sinais `< >` ou as palavras dentro deles (ex: `class="..."`), pois isso quebra o design.

---

## 🖼️ Como Alterar as Imagens

Existem duas formas de trocar as imagens. A **Opção 1** é a mais recomendada e fácil.

### Opção 1: Substituição de Arquivo (Recomendado)
1. Prepare a sua nova imagem e garanta que ela tenha o mesmo formato (JPG ou PNG) da original.
2. Renomeie sua nova imagem com o **mesmo nome exato** da imagem antiga que está na pasta `assets`.
   * *Exemplo:* Se quiser trocar a capa, salve sua nova imagem como `ebook.png`.
3. Arraste sua nova imagem para a pasta `assets` e confirme a substituição.

### Opção 2: Alteração no Código
1. Coloque a nova imagem na pasta `assets`.
2. No `index.html`, procure pela tag `<img>`.
3. Mude o nome do arquivo dentro de `src="./assets/NOME_DA_IMAGEM"`.

### 📏 Dimensões Recomendadas
Para manter a qualidade e o layout:
- **Capa do Ebook (Hero):** Formato vertical (aprox. 800x1200px), fundo transparente (.png).
- **Foto da Autora:** Quadrada (500x500px), rosto centralizado.
- **Ícones/Fundos:** Manter proporção original.

---

## 🚀 Publicação
Esta página está pronta para hospedagem. Caso utilize o **Netlify**:
1. Certifique-se de que o arquivo `output.css` está atualizado.
2. Arraste a pasta inteira do projeto para a área de "Drop" do Netlify.