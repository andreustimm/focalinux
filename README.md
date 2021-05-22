# Foca Linux

Eu senti falta de uma versão em **.epub** para ser lido em leitores digitais com maior facilidade. Então eu gerei elas, estou anexando elas no e-mail, se quiser publicar elas no portal. Ou regerar elas, você pode usar o **PANDOC**, com o comando abaixo.

```bash
wget https://www.guiafoca.org/download/static/segur/focalinux-4-html.zip
unzip focalinux-4-html.zip
cd focalinux-4-html
pandoc -f html -t epub3 -o novo_focalinux_04_seguranca.epub *.html
```

Arquivos gerados em 31/12/2020

## Iniciante
v 5.02 | 20200727 08:03

## Iniciante + Intermediário
v 6.02 | 20200727 08:44

## Intermediário
v 6.02 | 20200727 08:14

## Avançado
v 7.02 | 20200727 08:31

## Segurança
v 1.00 | 20200727 22:44
