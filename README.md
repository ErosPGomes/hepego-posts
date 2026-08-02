# hepego-posts

Artes das postagens da Hépego, por mês, para publicação via Zernio (URL pública, sem consumir quota de upload).

Uma subpasta por mês. Os arquivos NÃO devem ser sobrescritos depois de agendados.

## Estrutura

- **Raiz** (`agosto/`, `setembro/`, `outubro/`, `novembro/`, `dezembro/`) — artes de **2026**, em PNG 2048px.
  Já agendadas: não sobrescrever, não renomear, não apagar.
- **`2027/<mes>/post-NN.jpg`** — artes de **2027**, 317 arquivos, JPEG 2048px q92 progressivo
  (~740 KB cada, ~248 MB no total). Em JPEG porque as mesmas 317 artes em PNG somariam
  ~1,6 GB e estourariam o limite de push do GitHub; o Instagram recomprime para 1080px na
  publicação, então não há perda visível.

O número `NN` é a ordem do post dentro do mês, igual à coluna `ID` da planilha de agendamento
(`2027-03-14` = março, post 14 = `2027/marco/post-14.jpg`).

## URL pública das artes

```
https://raw.githubusercontent.com/ErosPGomes/hepego-posts/main/2027/<mes>/post-NN.jpg
```

As pastas de mês usam nomes sem acento (`marco`, não `março`) para dispensar codificação na URL.
A planilha de agendamento já traz a URL pronta na coluna `URL da arte`.
