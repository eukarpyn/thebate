# The Bate

Jogo de festa "verdade ou mentira?" — página única, sem servidor, sem custo.

## Como publicar no GitHub Pages (grátis)

1. **Crie uma conta no GitHub**, se ainda não tiver: https://github.com/signup

2. **Crie um repositório novo**:
   - Clique no "+" no topo da página → "New repository"
   - Dê um nome, por exemplo `the-bate`
   - Marque como **Public** (obrigatório para o Pages gratuito)
   - Não marque "Add a README" (já temos um)
   - Clique em "Create repository"

3. **Envie os arquivos desta pasta** para o repositório:
   - Na página do repositório recém-criado, clique em "uploading an existing file"
   - Arraste **todos os arquivos e pastas daqui** (`index.html`, `manifest.json`, e a pasta `icons` inteira) para a área de upload
   - Role para baixo e clique em "Commit changes"

4. **Ative o GitHub Pages**:
   - No repositório, vá em "Settings" (aba no topo)
   - No menu da esquerda, clique em "Pages"
   - Em "Source", selecione a branch `main` e a pasta `/ (root)`
   - Clique em "Save"

5. **Espere 1-2 minutos** e seu jogo estará no ar em:
   `https://SEU-USUARIO.github.io/the-bate/`

   (troque `SEU-USUARIO` pelo seu nome de usuário do GitHub, e `the-bate` pelo nome que você deu ao repositório)

## Instalar como app no celular

Depois de publicado, qualquer pessoa pode abrir o link no celular e:
- **iPhone (Safari)**: tocar em "Compartilhar" → "Adicionar à Tela de Início"
- **Android (Chrome)**: tocar no menu (⋮) → "Adicionar à tela inicial" ou "Instalar app"

O jogo vai aparecer com ícone próprio, como um app de verdade, sem precisar de loja de aplicativos.

## Atualizações futuras

Quando quiser atualizar o jogo (novas cartas, ajustes), basta substituir o arquivo `index.html` no repositório pelo novo:
- Abra o arquivo `index.html` no repositório → ícone de lápis (editar) → cole o conteúdo novo → "Commit changes"
- Ou, se preferir, arraste o novo `index.html` por cima do antigo na tela de upload

O link não muda — fica sempre o mesmo endereço.

## Estrutura dos arquivos

```
index.html          → o jogo inteiro (HTML + CSS + JS + as 300 cartas)
manifest.json        → metadados para instalar como app (nome, cor, ícones)
icons/
  icon-192.png        → ícone do app (tamanho pequeno)
  icon-512.png        → ícone do app (tamanho grande)
  icon-maskable-512.png → ícone adaptável (Android)
  apple-touch-icon.png  → ícone para iPhone
  favicon-32.png        → ícone da aba do navegador
```
