```markdown
# Organizador de Scripts

Este proyecto contiene un script en Bash diseñado para organizar y mover archivos de script a directorios específicos. El objetivo es crear un conjunto de directorios, cada uno correspondiente a una letra del abecedario, y mover los archivos de script en función de su nombre.

## Descripción

El script realiza las siguientes acciones:
1. **Crea directorios** en la ruta especificada (en este caso, `/home/cesar/programas-3301/scripts-ejercicio2`) para cada letra del abecedario (`a` a `z`).
2. **Busca archivos** de script dentro del directorio base (por ejemplo, `script-1-a.sh`, `script-2-b.sh`).
3. **Mueve los archivos** a los directorios correspondientes a cada letra (por ejemplo, `a` a su directorio `a`, `b` a su directorio `b`, etc.).
4. Imprime un mensaje para cada archivo movido, indicando su ubicación original y el directorio al que fue movido.

Al final, se muestra un mensaje confirmando que todos los archivos han sido movidos.

## Requisitos

Este script está escrito en **Bash**, por lo que necesitas tener un entorno compatible con Bash (como Linux o macOS).

## Instalación

1. Clona este repositorio en tu máquina local:

   ```bash
   git clone https://github.com/tu_usuario/nombre-del-repositorio.git
   ```

2. Navega hasta el directorio del proyecto:

   ```bash
   cd nombre-del-repositorio
   ```

3. Asegúrate de que el script tenga permisos de ejecución:

   ```bash
   chmod +x tu_script.sh
   ```

## Uso

Para ejecutar el script, solo necesitas correrlo desde la terminal:

```bash
./tu_script.sh
```

El script organizará automáticamente los archivos en el directorio especificado, moviéndolos a las carpetas correspondientes.

## Ejemplo de salida

```bash
Moviendo /home/cesar/programas-3301/scripts-ejercicio2/script-1-a.sh a /home/cesar/programas-3301/scripts-ejercicio2/a/
Moviendo /home/cesar/programas-3301/scripts-ejercicio2/script-2-b.sh a /home/cesar/programas-3301/scripts-ejercicio2/b/
...
Archivos movidos a las carpetas correspondientes.
```

## Contribución

Si deseas contribuir a este proyecto, por favor sigue los siguientes pasos:

1. Realiza un fork de este repositorio.
2. Crea una nueva rama (`git checkout -b feature/nueva-caracteristica`).
3. Haz tus cambios y realiza commits (`git commit -am 'Agregada nueva característica'`).
4. Sube tus cambios a tu fork (`git push origin feature/nueva-caracteristica`).
5. Crea un pull request.

## Licencia

Este proyecto está bajo la Licencia MIT - consulta el archivo [LICENSE](LICENSE) para más detalles.
```

Este README es una descripción detallada de cómo funciona el script, cómo instalarlo, usarlo y cómo contribuir al proyecto. ¡Espero que te sirva!
