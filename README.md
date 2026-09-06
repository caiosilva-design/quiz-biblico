# 📖 Quiz Bíblico

Um app de jogos bíblicos, feito em HTML, CSS e JavaScript puro — sem dependências, sem build, um único arquivo (`index.html`) publicado direto no GitHub Pages.

🔗 **Jogue aqui:** https://caiosilva-design.github.io/quiz-biblico/

---

## 🎮 Jogos disponíveis

### 📖 Quiz Bíblico
Perguntas de múltipla escolha sobre o Antigo e o Novo Testamento, com:
- **238 perguntas**, organizadas por categoria (Antigo Testamento, Novo Testamento, Milagres, Parábolas, Curiosidades)
- **3 níveis de dificuldade** (Fácil, Médio, Difícil), filtráveis
- **4 modos de jogo:**
  - **Clássico** — sem pressão de tempo
  - **Contra o Relógio** — 15 segundos por pergunta
  - **Eliminatória** — um erro encerra a partida
  - **Modo Revisão** — sem placar, ideal para estudar
- **1 ou 2 jogadores**, alternando a vez
- Curiosidade explicativa após cada resposta

### 🕵️ Quem sou eu?
Jogo no estilo forca / "Roda a Roda": um personagem bíblico é sorteado, e o nome aparece em branco. Você vai revelando as letras usando o teclado na tela, arriscando o nome completo, ou pedindo dicas (que custam pontos). Errar letras custa uma das 6 "vidas" (🐑). 15 personagens bíblicos cadastrados, com dicas progressivas e uma curiosidade ao final de cada rodada.

### 🔤 Caça-palavras
Grade 12x12 gerada aleatoriamente a cada partida, com 10 nomes bíblicos escondidos em qualquer direção (horizontal, vertical, diagonal, e de trás pra frente também). Selecione arrastando da primeira até a última letra da palavra — funciona com mouse ou toque.

---

## 🛠️ Tecnologia

Tudo em um único arquivo `index.html`, sem frameworks:
- HTML + CSS puro (com variáveis CSS para suportar tema claro/escuro automaticamente)
- JavaScript vanilla (sem bibliotecas externas, exceto fontes do Google Fonts)
- Sem back-end, sem banco de dados — todo o estado do jogo vive na memória do navegador durante a partida

## 🚀 Como rodar localmente

Basta abrir o arquivo `index.html` diretamente no navegador. Não precisa de servidor, build ou instalação de dependências.

## 📦 Como publicar (GitHub Pages)

1. Suba o arquivo `index.html` na raiz do repositório
2. Vá em **Settings → Pages**
3. Em **Build and deployment → Source**, selecione **Deploy from a branch**
4. Escolha a branch `main` e a pasta `/ (root)`
5. Aguarde alguns minutos — o site fica disponível em `https://<seu-usuario>.github.io/<nome-do-repositorio>/`

## 🗺️ Próximos passos (roadmap)

- [ ] Devocional (seção reflexiva, mais textual)
- [ ] Mapa bíblico interativo
- [ ] Modo "Bíblia por idade" (visual e perguntas adaptadas para crianças)

## 📄 Licença

Projeto pessoal, de uso livre para fins educacionais e de entretenimento.
