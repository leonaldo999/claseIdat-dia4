# COMANDOS Y CONFIG GIT

0. Configuracion de GIT en nuestro Sistema Operativo (git config -- global user.name && user.email)
1. git init : Inicializa git en nuestros proyectos (solo se ejecuta una vez)
2. git status : Te menciona la situacion de tu proceso de GIT
3. git add . : Pasa cambios de working a staging area
4. git commit -m "Mi primer commit" : Pase cambios de stading area a repository
5. git log : Te muestra todos los commit
6. git log --oneline : Muestra los commit en una liena

## BRANCH

1. Main (Produccion) : El ambiente para los clientes
2. Desarrollo(Dev) : Nuestro ambiente para trabajar
3. QA(Calidad de Codigo) : Se prueban los desrrollos
4. UAT(Pre Producion) : Antes de mandar a produccion

Integracion (QA es uno mismo) => Hasta el dia Jueves(x) (Metodologia Screm)
1(Desarrollo) => 2(QA) => 3(UTA) => 4(Producion)

* Cada empresa tiene sus propios lineamientos
