# byOS Store Official (Privado)

Repositório oficial privado consumido exclusivamente pela loja **byStore** do **byOS** para listar, baixar e atualizar pacotes `.byt` assinados.

## Estrutura
- `catalog.json`: índice lido pela `byStore` para detectar novos apps, versões disponíveis e compatibilidade com a versão do byOS.
- `packages/`: pacotes `.byt` pequenos (< 50 MB). Para pacotes grandes (ex.: Chromium), publique o `.byt` em **GitHub Releases** deste repositório e aponte `download_url` para o asset da release.
