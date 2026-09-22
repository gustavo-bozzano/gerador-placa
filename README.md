# PlacaLab 3D

Gerador de placas 3D para mods de GTA, com prévia em Three.js e exportação em OBJ.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub.
2. Envie o conteúdo desta pasta para a branch `main`.
3. Abra **Settings > Pages** no repositório.
4. Em **Build and deployment**, escolha **GitHub Actions**.
5. Aguarde a execução chamada **Publicar no GitHub Pages** terminar.

O endereço publicado aparecerá na execução e na página de configurações do GitHub Pages.

## Arquivos usados pelo site

- `index.html`
- `styles.css`
- `font-data.js`
- `placa.obj`
- `placa.mtl`
- `padrao.png`
- `placa.png`
- `fonts/`

O fluxo de publicação copia somente esses arquivos. Arquivos do Blender, PSDs e materiais de trabalho podem permanecer no repositório sem fazer parte do site publicado.

Ao atualizar `placa.obj`, `padrao.png` ou `placa.png` e enviar a alteração ao GitHub, o site é publicado novamente automaticamente.
