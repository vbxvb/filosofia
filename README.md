# Além da Caverna — Uma Viagem com Platão

Projeto interdisciplinar de Filosofia, Linguagens e Web Design sobre o **Mito da Caverna** (Platão, Livro VII da *República*).

Construído exclusivamente com **HTML5 e CSS3 puros**, sem dependências de JavaScript ou frameworks, garantindo máxima compatibilidade, acessibilidade e conformidade com as diretrizes escolares.

---

## 📑 Estrutura do Site

O site é composto por 3 páginas integradas:

1. **`index.html` (Início)**:
   - Apresentação do tema e do problema filosófico ("E se tudo que você vê for uma sombra?").
   - Galeria com imagens históricas de Platão e gravuras clássicas da caverna.
   - Três conceitos fundamentais: As sombras (*doxa*), A ascensão (*paideia*) e A luz solar (*Agathón*).
   - Citação de referência do Livro VII da *República*.

2. **`alegoria.html` (A alegoria)**:
   - Narrativa detalhada dividida em quatro etapas: *As sombras*, *A libertação*, *A saída* e *O retorno*.
   - **Tabela Filosófica Completa**: Quadro comparativo sistematizando os 9 principais elementos e símbolos da alegoria, seus papéis na narrativa, seus significados filosóficos platônicos e analogias contemporâneas.
   - Provocação reflexiva sobre as ilusões do mundo atual.

3. **`reflexoes.html` (Reflexões & vídeo)**:
   - Análise da contemporaneidade do mito (redes sociais, algoritmos, bolhas de informação e desinformação).
   - **Player de Vídeo Integrado**: Espaço em formato 16:9 preparado para reproduzir o vídeo de 2 a 5 minutos gravado pelo grupo.
   - **Ficha Técnica do Projeto Escolar**: Seção dedicada com a identificação do trabalho, tema, referências e espaço para os nomes e atribuições dos integrantes da equipe.

---

## 🎬 Como adicionar o vídeo do grupo

Para incorporar o vídeo escolar gravado pela sua equipe:

1. Grave e edite um vídeo com duração entre **2 e 5 minutos**, com a participação de todos os membros do grupo.
2. Salve o arquivo com o nome exato:
   ```text
   video-caverna.mp4
   ```
3. Coloque esse arquivo dentro da pasta `videos/` na raiz do projeto:
   ```text
   filosofia-main/
   ├── videos/
   │   └── video-caverna.mp4
   ```
4. Ao abrir a página `reflexoes.html`, o navegador carregará automaticamente o vídeo no player.

> **Nota:** Caso prefiram hospedar o vídeo no YouTube, há instruções comentadas no código-fonte de `reflexoes.html` com o modelo de `<iframe>` pronto para uso.

---

## 🌐 Publicação no GitHub Pages

Este projeto foi estruturado com caminhos relativos e páginas estáticas limpas, ideal para publicação gratuita no GitHub Pages:

1. Suba os arquivos do projeto para o seu repositório no GitHub.
2. Acesse a aba **Settings** (Configurações) do repositório.
3. No menu lateral, clique em **Pages**.
4. Em **Branch**, selecione `main` (ou `master`) e pasta `/ (root)`.
5. Clique em **Save**. Em instantes, seu site estará no ar na URL fornecida pelo GitHub.

---

## 🎨 Identidade Visual

- **Paleta**: Noturna com realces em ouro antigo (`#171713`, `#22211c`, `#c6a36a`, `#dfc28d`).
- **Tipografia**: *Playfair Display* (títulos clássicos) e *DM Sans* (leitura limpa e fluida), carregadas via Google Fonts.
- **Símbolos Filosóficos**: `φ` (Phi / Filosofia), `✳` (Estrela do Saber), `◐` (Sombra / Luz).
