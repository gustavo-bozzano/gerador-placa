# PlacaLab 3D

Gerador de placas 3D Mercosul e cinza antiga para mods de GTA, com prévia em Three.js e exportação em OBJ.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub.
2. Envie o conteúdo desta pasta para a branch `main`.
3. Antes da primeira execução, abra **Settings > Pages** no repositório.
4. Em **Build and deployment**, escolha **GitHub Actions** como origem.
5. Abra **Actions** e execute novamente **Publicar no GitHub Pages** se a primeira tentativa já tiver falhado.

O endereço publicado aparecerá na execução e na página de configurações do GitHub Pages.

## Arquivos usados pelo site

- `index.html`
- `styles.css`
- `font-data.js`
- `placa.obj`
- `placa.mtl`
- `padrao.png`
- `padrao-azul.png`
- `padrao-vermelho.png`
- `placa.png`
- `placa_antigo.obj`
- `placa_antigo.mtl`
- `placa_antigo.png`

O fluxo de publicação copia somente esses arquivos. Arquivos do Blender, PSDs e materiais de trabalho podem permanecer no repositório sem fazer parte do site publicado.

Ao atualizar `placa.obj`, qualquer variação `padrao*.png` ou `placa.png` e enviar a alteração ao GitHub, o site é publicado novamente automaticamente.
O mesmo vale para os arquivos `placa_antigo.*` usados pelo modelo cinza.

Se `actions/configure-pages` informar `Get Pages site failed` ou `Not Found`, o Pages ainda não foi habilitado em **Settings > Pages**.
