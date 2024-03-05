---
date: 2018-10-06
title: Documentação Fácil com Doxie
linkTitle: Introdução ao Doxie
description: "O tema Doxie, alimentado pelo Hugo, permite que os construtores de projetos se concentrem na criação de conteúdo, sem a necessidade de construir um site."
author: Riona MacNamara ([@rionam](https://twitter.com/bepsays))
resources:
- src: "**.{png,jpg}"
  title: "Imagem #:counter"
  params:
    byline: "Foto: Riona MacNamara / CC-BY-CA"
---

**Este é um post comum que inclui uma imagem.**

Nos metadados iniciais de cada post, há um título, uma data e um resumo que é exibido na lista de posts.


## Incluindo uma Imagem

Aqui está uma imagem (`featured-sunset-get.png`) que inclui uma legenda e uma byline.


{{< imgproc sunset Fill "600x300" >}}
Obtendo e redimensionando uma imagem na versão 0.43 do Hugo
{{< /imgproc >}}


As seguintes especificações, que estão nos dados do post, são aplicadas a todas as imagens deste post:

