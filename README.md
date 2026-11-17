# Eco Noturno

Labirinto escuro onde voce e uma luz que encolhe. Funciona no navegador e pode ser instalado como app (PWA).

## Publicar no GitHub Pages
1. Crie um repositorio no GitHub e envie **todos os arquivos desta pasta** para a raiz dele (`index.html`, `sw.js`, `manifest.webmanifest`, `icons/`, `.nojekyll`).
2. No repositorio: **Settings > Pages > Build and deployment**. Em *Source* escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`, e salve.
3. Em 1 a 2 minutos o site fica em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

## Instalar no celular
- **Android (Chrome):** abra o site, toque em **Instalar app** no menu do jogo ou no menu do Chrome (tres pontos) > *Instalar app* / *Adicionar a tela inicial*.
- **iPhone (Safari):** botao de compartilhar > **Adicionar a Tela de Inicio**. (O iPhone nao mostra o botao "Instalar app" do jogo.)
- **Computador (Chrome/Edge):** icone de instalar na barra de endereco.

Depois da primeira visita o jogo abre mesmo sem internet. A unica coisa que precisa de internet sao as fontes do Google, que ficam salvas depois de carregadas.

## Atualizar o jogo
Ao trocar o `index.html`, aumente o numero em `VERSION` dentro de `sw.js` (por exemplo `eco-noturno-v2`) para os celulares pegarem a versao nova.
