
## Ciclo de desarrollo

Tenemos tres branchs para el desarrollo:

Dev: Se realizará todos los cambios de código ahí.
Production: Se probarán todos los cambios unificados.
Master: Ya probado los cambios en production se suben a master para hacer el deploy manual.



## Deploying

```sh
$ git clone https://github.com/CodeandoMexico/codeandomexico.git # o clona tu fork
$ cd codeandomexico
$ git add *cambios*
$ git commit -m "Mis cambios"
$ git push origin master
```
