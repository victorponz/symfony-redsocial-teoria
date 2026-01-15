---
typora-copy-images-to: ../assets/img/
typora-root-url: ../../
title: Primeros pasos
layout: post
categories: parte1
conToc: true
permalink: primeros-pasos
---

## 1.1 Crear proyecto

Comencemos por un proyecto vacío:

```
composer create-project symfony/skeleton:"6.4.*" symfony-redsocial
```

Y instalamos los componentes necesarios:

```
composer require symfony/maker-bundle --dev
composer require symfony/twig-bundle
composer require symfony/asset
composer require symfony/orm-pack
composer require symfony/profiler-pack
composer require form security validator
```



## 1.2 Gestión de Usuarios

Al igual que hicimos en el proyecto [Symfony Contactos](https://victorponz.github.io/symfony-contactos-teoria/posts/seguridad-y-control-de-accesos/), crearemos la gestión de usuarios
