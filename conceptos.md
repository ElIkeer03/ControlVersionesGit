
# Glosario de conceptos básicos: Git / GitHub

## Repositorio
Un repositorio es como una carpeta donde se almacenan todos los archivos relacionados con un proyecto, incluyendo código, documentación o ejemplos. Puede ser de dos tipos:  
- **Público**, visible para cualquier persona.  
- **Privado**, con acceso restringido únicamente a ciertos usuarios.  

## Archivo README
El archivo README es un documento fundamental dentro del repositorio que contiene información básica para entender y usar el proyecto. Suele incluir el nombre del proyecto, una descripción general, créditos, índice de contenidos, instrucciones de uso y detalles sobre la licencia.

## Rama (Branch)
Una rama es una copia del contenido de un proyecto que permite trabajar en paralelo sin alterar el proyecto original. La **rama master (o main)** contiene la versión principal del proyecto, mientras que las ramas remotas o locales permiten realizar cambios de manera independiente. Un error en estas ramas no afecta al repositorio principal hasta que se integren los cambios.

## Clone y Fork
El comando **clone** se utiliza para crear una copia local de un repositorio existente, de modo que se pueda trabajar de manera offline.  
Un **fork**, en cambio, genera una copia del repositorio original dentro del perfil de un usuario en GitHub, permitiendo trabajar online y proponer cambios sin modificar directamente el proyecto original.

## Commit
Un commit es un registro de los cambios realizados en los archivos de un proyecto. Funciona como una “fotografía” de un estado específico del código, en la que quedan guardadas las modificaciones. Los commits se almacenan inicialmente en la rama local.

## Push y Pull Request
Un **push** es la acción de enviar los commits realizados en la copia local hacia la rama principal de un repositorio remoto.  
Un **pull request** es una solicitud formal para integrar esos cambios en el proyecto original, lo que generalmente implica que otros revisen y aprueben las modificaciones antes de que se fusionen.

## Merge
El merge es el proceso mediante el cual los cambios de una rama se integran con otra, normalmente desde una rama remota hacia la rama principal (master o main). Una vez realizado el merge y aprobados los cambios, ambas ramas quedan idénticas.

## Áreas de trabajo en Git
Git organiza el trabajo en tres áreas distintas.  
- **Working Directory**: es el espacio donde se editan y modifican los archivos del proyecto.  
- **Staging Area**: es el área de preparación en la que se seleccionan los archivos que se desean guardar en la próxima versión.  
- **Repository**: es el almacenamiento definitivo en el que se guardan todas las versiones y el historial de cambios.  
