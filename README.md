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
├── index.html      # Página principal (hero, menú, sobre nosotros, pedido)
├── style.css        # Estilos del sitio
└── README.md        # Este documento
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

> Reemplazar esta sección con capturas de pantalla de `git log --oneline`
> y del historial de commits visto en GitHub antes de entregar.

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
