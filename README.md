# The Bate

Jogo de festa "verdade ou mentira?" — página única, sem servidor, sem custo.

# Instalar como app no celular

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
