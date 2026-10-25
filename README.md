# Xeque Treino

App de xadrez para treinar aberturas contra o Stockfish. Funciona no navegador e pode ser instalado no celular (PWA), inclusive sem internet.

## Publicar no GitHub Pages (grátis)

1. Entre em https://github.com e crie um repositório novo, **público**, chamado `xeque-treino`.
2. No repositório, toque em **Add file > Upload files**, selecione **todos os arquivos desta pasta** (são cerca de 20, sem subpastas) e envie de uma vez. Depois toque em **Commit changes**.
3. Vá em **Settings > Pages**. Em **Source**, escolha **Deploy from a branch**, depois a branch `main` e a pasta `/ (root)`, e salve.
4. Espere 1 ou 2 minutos. O endereço do app será `https://SEU-USUARIO.github.io/xeque-treino/`.

## Instalar no celular

- **Android (Chrome):** abra o endereço e toque em **Instalar app** (botão no topo do app) ou no menu ⋮ > **Instalar app**.
- **iPhone (Safari):** toque em Compartilhar > **Adicionar à Tela de Início**.

Depois de instalado, o app abre em tela cheia e funciona sem internet.

## Atualizar

Envie de novo os arquivos que mudaram. Se mudar qualquer arquivo, troque também o valor de `VERSION` no começo de `sw.js` (por exemplo, `xeque-v2`). O celular pega a versão nova na segunda vez que o app for aberto com internet.
