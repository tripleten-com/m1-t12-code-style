# Estilo de código: principios de código limpio

## Bifurcar un repositorio

Para hacer una copia de un repositorio, haz clic en el botón Fork (bifurcar) en la esquina superior derecha de la página del repositorio. Esto producirá un duplicado del proyecto en tu cuenta de GitHub. Si no tienes una cuenta, crea una.

![fork button](https://raw.githubusercontent.com/PraktikumJava/public-resources/master/fork.png)


## Clonar un repositorio

Abre la pestaña Repositories (repositorios) en tu página de GitHub y selecciona el repositorio que bifurcaste en la etapa anterior. Haz clic en el botón Code (código) en el lado derecho de la página:

![botón de bifurcación (fork)](https://github.com/practicum-com/public-resources/blob/main/clone.png)


Verás una ventana donde puedes copiar la dirección del repositorio. Esto será necesario para clonarlo. Ahora abre el símbolo del sistema y muévete a la carpeta donde vas a guardar el repositorio. Introduce el comando git clone y la dirección del repositorio:

```bash
git clone https://github.com/EL_NOMBRE_DE_TU_CUENTA_AQUÍ/code-style-and-effective-work-in-ide-code-style.git
```

## Importar un proyecto en IDEA

Selecciona el elemento Open (abrir) o Import (importar) en el cuadro de diálogo al iniciar IDEA.

![botón de bifurcación (fork)](https://raw.githubusercontent.com/PraktikumJava/public-resources/master/import.png)

En la ventana para abrir archivos, elige la carpeta con el repositorio clonado y haz clic en el botón Open. Ten en cuenta que debes abrir todo el directorio. Después de esto, el proyecto se agregará a IntelliJ IDEA.
