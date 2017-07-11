---
title: Guardando Secretos
author: Diego Gruber
date: '2017-07-06'
weight: 1
slug: guardando-secretos
categories: []
tags: []
---

A menudo nuestros desarrollos requieren que guardemos credenciales para conectarnos a bases de datos, APIs, etc. Una estrategia habitual es guardar estas credenciales en ficheros externos al repositorio de código para evitar que se expongan accidentalmente. Hay situaciones en las que esto puede generar ciertas dificultades.

El package [`secret`](https://cran.r-project.org/web/packages/secret/index.html)  está diseñado para poder guardar credenciales dentro de un repositorio de código de forma segura utilizando encriptación con claves públicas y privadas. Está desarrollado por un par de cracks así que creo que valdrá la pena probarlo.