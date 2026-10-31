# E+ v25 — Publicação no GitHub e Vercel

Aplicação estática, sem build, com HTML, CSS e JavaScript integrados no `index.html`.

## Publicação

1. Extraia o ZIP e abra a pasta `Eplus-v25-Publicacao`.
2. Crie um repositório no GitHub e envie **os arquivos que estão dentro dessa pasta para a raiz do repositório** (não apenas o ZIP).
3. Confirme que o GitHub mostra `index.html` e `vercel.json` na raiz.
4. Na Vercel, importe o repositório, selecione **Other** como framework, deixe **Build Command** vazio e use **Root Directory** `./`.
5. Clique em Deploy. Se já tiver um projeto, faça push da alteração e aguarde o novo deploy.

## Armazenamento

Os dados são guardados em `localStorage` no navegador e não são sincronizados entre dispositivos. Use a aba Backup para exportar seus dados. O projeto não possui backend, autenticação ou banco de dados.

## Teste local

Abra `index.html` no navegador e confira a aparência e os menus. Para simular a hospedagem, execute `python -m http.server 8000` dentro da pasta e acesse `http://localhost:8000`.
