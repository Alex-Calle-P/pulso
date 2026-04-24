# Guía de Contribución (Forking Workflow)-Proyecto Pulso

Este documento detalla el proceso para colaborar en el proyecto siguiente:

## 1. Crear un Fork
El primer paso es crear una copia personal del repositorio oficial en GitHub.

[AQUÍ_VA_TU_CAPTURA_DEL_FORK]

## 2. Clonar el Repositorio
Para trabajar localmente, clonamos nuestro fork usando la terminal:

```bash
git clone [https://github.com/Alex-Calle-P/pulso.git](https://github.com/Alex-Calle-P/pulso.git)

[CAPTURA_02_CLONE_EXITOSO]

## 3. Crear una Rama (Branch)
Para mantener el orden, creamos una rama específica para la tarea asignada. Esto evita conflictos con la rama principal (main):

Bash
git checkout -b docs/flujo-de-trabajo
[CAPTURA_03_CREACION_DE_RAMA]

##4. Realizar Commit y Push
Después de crear o modificar los archivos, guardamos los cambios localmente y los subimos a nuestro fork en GitHub:

Bash
git add .
git commit -m "docs: guía de flujo de trabajo con capturas"
git push origin docs/flujo-de-trabajo
[CAPTURA_04_COMMIT_Y_PUSH_TERMINAL]

##5. Abrir Pull Request
El paso final es proponer nuestros cambios al repositorio original mediante un Pull Request, vinculando el Issue correspondiente.

[CAPTURA_05_PULL_REQUEST_EN_GITHUB]