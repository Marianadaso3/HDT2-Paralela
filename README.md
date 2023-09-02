# HDT2-Paralela


## Requirements

Librerias 

- <mpi.h>     
- <string.h>
- <stdio.h>
  
## Settings

Clone the project using the following commands from console

```bash
git https://github.com/Marianadaso3/HDT2-Paralela.git
```
Instalations

```bash
sudo apt-get update
```

```bash
sudo apt-get install lam4-dev
```

```bash
lamboot
```
-----------------------------------------------------

Compile

mpiHello.c
```bash
mpicc mpiHello.c -o mpiHello
```

mpiHello2.c
```bash
mpicc mpiHello2.c -o mpiHello2
```

mpiHello3.c
```bash
mpicc mpiHello3.c -o mpiHello3
```

-----------------------------------------------------

Run code

If you need permitions:

mpiHello.c
```bash
chmod +x mpiHello
```

If you dont need permitions:

mpiHello.c
```bash
./mpiHello
```

mpiHello2.c
```bash
./mpiHello2
```

mpiHello3.c
```bash
mpirun -np 2 ./mpiHello3
```



