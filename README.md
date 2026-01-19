# Desafio Évera Tech - Landing Page "A Rota do Dólar"

Este projeto é a resposta ao desafio técnico para a vaga de Developer Partner. Consiste na transformação de um wireframe validado (modelo Ebook) em uma Landing Page de alta performance.

## 🛠️ Stack Tecnológica (Alinhada aos Requisitos)
- **HTML5 Semântico:** Estrutura otimizada para SEO e acessibilidade (uso de `header`, `main`, `section`, `footer` e atributos ARIA).
- **Tailwind CSS v4:** Utilizado para estilização rápida, responsiva e leve, conforme encorajado no desafio.
- **Design Responsivo:** Layout fluido (Mobile-First) adaptável a celulares, tablets e desktops.

## 🚀 Performance & Netlify Ready
O projeto foi estruturado para ser leve:
- Imagens otimizadas localizadas em `./assets`.
- CSS minificado e purgado via Tailwind CLI.
- Estrutura de pastas pronta para "Drag & Drop" no Netlify.

## 📂 Como Rodar Localmente

1. **Instalar dependências:**
   ```bash
   npm install
   ```
2. **Compilar o CSS (Tailwind v4):**
  ```bash
  npx @tailwindcss/cli -i ./input.css -o ./output.css --watch
  ```
3. **Executar:** Utilize o Live Server ou abra o index.html no navegador.
