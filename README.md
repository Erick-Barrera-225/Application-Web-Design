# Diseño de Aplicaciones Web

## Datos personales
- **Nombre completo:** Erick Barrera Rodríguez
- **Matrícula:** 2959636
- **Carrera:** Ingeniería en Desarrollo de Software
- **Semestre:** 8° semestre

## Datos de la materia
- **Nombre de la asignatura:** Diseño de Aplicaciones Web
- **Nombre del profesor:** Cristopher Gerardo Gaytán Díaz

## ¿Qué es Markdown?
Markdown es un lenguaje de marcado ligero que se utiliza para dar formato a texto plano
de manera sencilla y legible. Permite crear documentos estructurados sin necesidad de
utilizar etiquetas complejas, por lo que es ideal para archivos README, documentación
técnica y descripciones de proyectos.

## Opciones de etiquetado en Markdown

Markdown ofrece diversas opciones de etiquetado que permiten dar formato al texto de manera sencilla y estructurada, facilitando la lectura y organización de la información.

### Títulos y subtítulos
Se utilizan para organizar el contenido en secciones jerárquicas.  
Se representan con el símbolo `#`. Entre más símbolos se utilicen, menor será el nivel del título.

Ejemplo:
# Título principal
## Subtítulo
### Subtítulo de nivel 3

### Texto en negritas y cursivas

Se utilizan para resaltar palabras o frases importantes dentro del texto.

Ejemplo:

**Texto en negritas**  
*Texto en cursivas*  
***Texto en negritas y cursivas***

### Listas ordenadas y no ordenadas

Las listas permiten organizar información de forma clara y estructurada.

Lista no ordenada:

- Elemento uno
- Elemento dos
- Elemento tres

Lista ordenada:

1. Primer elemento
2. Segundo elemento
3. Tercer elemento

### Enlaces

Los enlaces permiten redirigir al usuario a páginas web o recursos externos.

Ejemplo:

[GitHub](https://github.com/Erick-Barrera-225/Application-Web-Design)

### Imágenes

Las imágenes se utilizan para complementar visualmente la información del documento.

Ejemplo:

![Markdown Syntax](https://arminreiter.com/wp-content/uploads/2020/04/md-preview.png)

### Bloques de código

Los bloques de código permiten mostrar comandos o fragmentos de código respetando su formato original.

Ejemplo:

```bash
git status
git add .
git commit -m "Mensaje del commit" 
```

## Comandos de Git

En esta sección se describen los principales comandos de Git utilizados durante el desarrollo del proyecto, así como su función dentro del control de versiones.

### Ver el estado del repositorio

Este comando permite conocer el estado actual del repositorio, mostrando qué archivos han sido modificados, cuáles están en el área de preparación (stage) y cuáles aún no han sido agregados.

```bash
git status
```

### Agregar archivos al Stage

Git utiliza un área intermedia llamada **Stage** donde se preparan los archivos antes de confirmarlos en un commit.

#### Agregar un archivo específico

Este comando agrega un solo archivo al área de preparación.

```bash
git add README.md
```

#### Agregar todos los archivos

Este comando agrega todos los archivos modificados al área de preparación.

```bash
git add .
```

### Crear un commit con comentario

El commit guarda los cambios realizados en el repositorio junto con un mensaje descriptivo que explica qué se hizo.

```bash
git commit -m "Mensaje descriptivo del commit"
```

### Subir cambios al repositorio remoto

Este comando envía los commits locales al repositorio remoto alojado en GitHub.

```bash
git push origin main
```

### Manejo de ramas

Las ramas permiten trabajar en diferentes versiones del proyecto sin afectar la rama principal.

#### Crear una nueva rama

```bash
git branch nombre-rama
```

#### Listar ramas existentes

```bash
git branch
```

#### Cambiar de rama

```bash
git checkout nombre-rama
```

#### Eliminar una rama

```bash
git branch -d nombre-rama
```

### Regresar el repositorio a un commit específico (rollback)

Este comando permite regresar el proyecto a un estado anterior utilizando el identificador del commit.

```bash
git reset --hard ID_DEL_COMMIT
```