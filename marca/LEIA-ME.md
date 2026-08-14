# Marca do SignalBot

Estes arquivos existem para serem **servidos publicamente** — hoje, o logo dos
e-mails transacionais. E-mail não aceita imagem embutida (o Gmail descarta
`data:`), então a imagem precisa de um endereço na internet.

| Arquivo | Para quê |
|---|---|
| `simbolo-128.png` | o e-mail. Aparece a ~48 px; 128 cobre tela retina pesando 4 KB |
| `simbolo-512.png` | quando alguém pedir "o logo" |
| `banner-email.png` | o cabeçalho dos e-mails. 960 px, exibido a 480 — o dobro cobre tela retina |

🔴 **Não edite nada aqui à mão.** Estes PNGs são *gerados* — a fonte é
`marca/gerar_marca.py`, no repositório do produto, a partir dos números do
Manual do Símbolo v1.0. Uma cópia editada aqui viraria uma segunda verdade
sobre a geometria, e a marca passaria a divergir de si mesma.

Para trocar: regere lá, copie para cá e publique. O caminho (`marca/...`) faz
parte da URL que os e-mails já enviados apontam — **mudar o nome do arquivo
quebra a imagem de todo e-mail antigo**, então prefira substituir o conteúdo.
