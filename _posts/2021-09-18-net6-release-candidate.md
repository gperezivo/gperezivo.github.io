---
layout: post
title:  "Cómo instalar la RC1 de .NET 6 en Linux"
date:   2021-09-18 00:04:24 +0200
tags: .NET Novedades 
---

### Ya tenemos Release Candidate de __.NET 6__!
A principios de semana han liberado la primera release candidate de __.NET 6__

Si te ha pasado como a mi, que has ido instalando las versiones preview de __.NET 6__ tanto en Windows como en Linux (WSL o nativo) seguramente estés en el mismo punto... preguntandote como actualizar a la nueva rc1

Es bastante sencillo, con este sencillo script es suficiente:

```bash
#Si como en mi caso, ya lo tenias de instalaciones anteriores, omite el primer paso
mkdir $HOME/dotnet_install
cd $HOME/dotnet_install
curl -L https://aka.ms/install-dotnet-preview -o install-dotnet-preview.sh
sudo bash install-dotnet-preview.sh
```

Con esto actualizarás de la preview-7 (en mi caso) a la RC1 o la instalarás si no tenias ninguna versión previa.

![dotnet 6 rc1](/assets/dotnet-6-rc1.png)

Enjoy!


