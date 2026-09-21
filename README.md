# Sazón Cusco — Sistema web de pedidos de comida local

Proyecto del **Laboratorio 1: Introducción al entorno de desarrollo y Git**
(Ingeniería de Software).

## 1. Descripción

Sazón Cusco es el prototipo web de una startup cusqueña que quiere conectar
picanterías y cocinas familiares del centro histórico de Cusco con vecinos
que desean pedir comida típica a domicilio. Esta primera versión es un sitio
estático de una sola página que muestra el menú y permite iniciar un pedido
por WhatsApp.

## 2. Objetivo del laboratorio

Configurar un entorno de desarrollo y aplicar control de versiones con Git
en un proyecto básico, gestionando un repositorio local y uno remoto en
GitHub.

## 3. Tecnologías utilizadas

- HTML5
- CSS3
- Git / GitHub
- Visual Studio Code

## 4. Estructura del proyecto

```
pedidos-cusco/
├── index.html            # Página principal (hero, menú, sobre nosotros, pedido)
├── style.css              # Estilos del sitio
├── README.md              # Este documento
└── evidencias/            # Capturas del proceso de Git (para el entregable)
    ├── 01-configuracion-git.png
    ├── 02-git-init.png
    ├── 03-git-add-commit.png
    ├── 04-crear-repositorio-github.png
    ├── 05-git-remote-add-push.png
    └── 06-commits-en-github.png
```

## 5. Cómo ver el sitio

1. Clonar el repositorio:
   ```bash
   git clone URL_DEL_REPOSITORIO
   ```
2. Entrar a la carpeta del proyecto y abrir `index.html` en el navegador
   (doble clic, o clic derecho → "Open with Live Server" en VS Code).

## 6. Flujo de trabajo con Git

1. `git init` para inicializar el repositorio local.
2. `git add .` para preparar los archivos.
3. `git commit -m "mensaje"` para registrar cada avance.
4. `git remote add origin URL` para enlazar el repositorio remoto en GitHub.
5. `git push -u origin main` para subir los cambios.

## 7. Evidencias de commits

**1. Configuración de usuario en Git**
![Configuración de git config --global](evidencias/01-configuracion-git.png)

**2. Inicialización del repositorio local**
![git init](evidencias/02-git-init.png)

**3. Primer commit (`git add .` y `git commit -m "Primer commit"`)**
![git add y git commit](evidencias/03-git-add-commit.png)

**4. Creación del repositorio remoto en GitHub**
![Crear repositorio en GitHub](evidencias/04-crear-repositorio-github.png)

**5. Conexión con el remoto y `git push`**
![git remote add origin y git push](evidencias/05-git-remote-add-push.png)

**6. Commit reflejado en GitHub**
![Historial de commits en GitHub](evidencias/06-commits-en-github.png)

## 8. Reflexión

**¿Por qué Git es crítico en proyectos colaborativos?**
Porque permite que varias personas trabajen sobre el mismo código al mismo
tiempo sin sobrescribir el trabajo de los demás, registra quién hizo cada
cambio y cuándo, y facilita combinar (merge) el trabajo de distintos
integrantes del equipo.

**¿Qué problemas evita?**
Evita la pérdida de código por sobrescritura accidental, permite volver a
una versión anterior si algo falla, elimina la necesidad de mandar archivos
por correo o USB con nombres como "final_v2_definitivo.html", y deja un
historial claro de la evolución del proyecto.

## 9. Autor

- Nombre: _completar_
- Curso: Ingeniería de Software
- Fecha: _completar_
