# Práctica 1

## Comandos

### Git clone
Se usa para copiar un repositorio de Git existente en un nuevo directorio local.

#### Logs:
Cloning into 'hello-world'...
remote: Enumerating objects: 38, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 38 (delta 0), reused 0 (delta 0), pack-reused 34
Unpacking objects: 100% (38/38), 59.54 KiB | 1.35 MiB/s, done.

### Git status
Permite mostrar el estado del directorio de trabajo y del área del entorno de ensayo.

#### Logs:
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        hello-world/

nothing added to commit but untracked files present (use "git add" to track)

### Git add
Selecciona el archivo especificado y lo mueve al área de preparación, marcándolo para incluirlo en la próxima confirmación.

### Git commit
Guarda todos los cambios hechos en la zona de montaje o área de preparación (staging area), junto con una breve descripción del usuario.

#### Logs:
[main cc795c1] Primeros cambios
 2 files changed, 2 insertions(+)
 create mode 100644 Practica1
 create mode 160000 hello-world

### Git push
Se usa para cargar contenido del repositorio local a un repositorio remoto.

#### Logs:
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 341 bytes | 341.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/alexx-asm/ALEJANDROALAMAN-GIT-PAT-practica-1
   6381d58..cc795c1  main -> main

### Git checkout
Cambiar entre diferentes versiones de una entidad objetivo. Opera sobre tres entidades distintas: archivos, confirmaciones y ramas.

#### Logs:
Your branch is up to date with 'origin/main'.

### Java

#### Logs:
java 17.0.6 2023-01-17 LTS
Java(TM) SE Runtime Environment (build 17.0.6+9-LTS-190)
Java HotSpot(TM) 64-Bit Server VM (build 17.0.6+9-LTS-190, mixed mode, sharing)

### Maven:

#### Logs:
Apache Maven 3.8.7 (b89d5959fcde851dcb1c8946a785a163f14e1e29)
Maven home: C:\Program Files\apache-maven-3.8.7
Java version: 16.0.2, vendor: International Business Machines Corporation, runtime: C:\Program Files\Java\jdk-16.0.2+7
Default locale: es_ES, platform encoding: Cp1252
OS name: "windows 10", version: "10.0", arch: "amd64", family: "windows"

### Docker:

#### Logs:
Docker version 20.10.22, build 3a2c30b
