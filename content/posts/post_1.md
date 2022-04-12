---
title: "Stash estelar"
date: 2022-04-11
description: 'Usando Stash para reservar los cambios sin necesariamente hacerle add, commit'
---

Creo que ahora que estamos empezando todos con **git** nos damos cuenta que cuando tenemos modificaciones y estamos practicando, 
nos damos cuenta que necesitamos cambiar de rama. 

Pero tenemos tenemos cambios en nuestra rama actual que no sabemos si los queremos mandar a commit, necesitamos de forma rapida revisar otra rama,
sin dejar rastro de nuestros cambios por el momento, es aqui donde hacemos uso de stash, despues de conocer los cambios con git status, 
hacemos git add de los archivos modidicados, y entonces reservamos estas modificaciones haciendo "git stash".
Esto genera una "Pila" de los cambios reservados en local.
