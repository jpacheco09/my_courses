# Introduction to Machine Learning and Deep Learning

Notas y codigos derivados del curso _Introduction to Machine Learning and Deep Learning_.

## Requisitos

Al momento de iniciar el curso (06-09-2023) se recomienda instalar los siguientes componentes:

- Python 3.11 o superior
- Bibliotecas de python:
   numpy
   matplotlib
   matplotlib-inline
   flashtext
   pandas
   scipy
   scikit-learn
   scikit-learn-intelex
   imbalanced-learn
- Docker Desktop 4.22.1
- Visual Studio Code con las siguientes extensiones
  - __TODO:__ add installation instructions, similar to the [modern cpp must have tools wiki](https://github.com/nachovizzo/must-have-tools/wiki).

## Instalación

===
Proporciona instrucciones sobre cómo instalar el proyecto localmente. Incluye pasos específicos para configurar el entorno y las dependencias necesarias. Puedes utilizar virtual environments para mantener el ambiente aislado y limpio.

### Python

===
Primero, se instalan los paquetes para administrar el entorno virtual.

``` bash
pip install virtualenv virtualenvwrapper
```

Iniciar un entorno virtual.

```python
mkvirtualenv cv -p python3
pip install -r requirements.txt
```

### Docker

===

## Estructura del Proyecto

Explica la estructura general del proyecto y la función de cada directorio o archivo importante.

```text
proyecto/
    ├── app/
    │   ├── app.py
    │   └── ...
    ├── db/
    │   ├── db.py
    │   └── ...
    ├── docker/
    │   ├── Dockerfile.app
    │   └── ...
    ├── tests/
    │   ├── test_funcionalidad.py
    │   └── ...
    ├── README.md
    ├── requirements.txt
    └── ...
```

## Contribución

Indica cómo otros desarrolladores pueden contribuir al proyecto. Esto podría incluir información sobre cómo presentar issues, proponer nuevas funcionalidades, enviar pull requests y más.

1. Clona el repositorio.
2. Crea una nueva rama: `git checkout -b nueva-funcionalidad`.
3. Realiza tus cambios y commitea: `git commit -m "Agrega nueva funcionalidad"`.
4. Envía tus cambios: `git push origin nueva-funcionalidad`.
5. Abre un pull request explicando los cambios y su propósito.

## Créditos

Si tu proyecto se basa en otros proyectos o tiene colaboradores, reconócelos aquí y proporciona enlaces a sus perfiles o repositorios.

## Licencia

Indica la licencia bajo la cual se distribuye el proyecto. Por ejemplo, puedes utilizar la Licencia MIT, la Licencia Apache, entre otras.

---
