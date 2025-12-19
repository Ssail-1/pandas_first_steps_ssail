# Primeros pasos con Pandas

Ejecuta las celdas del notebook [1_primeros_pasos_con_Pandas.ipynb](./1_primeros_pasos_con_Pandas.ipynb)


## Que estoy haciendo?

### Instrucciones para entorno

1. fork del repo
2. Clonamos de actual
3. `git remote -v` para confirmar que esta apuntando a nuestro gitHub
4. Crear entorno virtual
   1. EN MI CASO: `/usr/bin/python3.12 -m venv .venv`
   2. source .venv/bin/activate
   3. `python --version` y `which python` para confirmar el entorno
5. Instalar dependencias
   1. `pip install -r requirements.txt`
6. Ya tiene `.gitignore` pero te recomiendo modificarlo, puedes basarte en el mio.
7. `pip install --upgrade pip` recomendado no obligatorio

### Instrucciones de actividad

1. `jupyter lab` abrimos jupyter lab
2. Ejecuta todas las celdas:
   1. En el notebook:
   2. Menú Run
   3. Run All Cells
      - Comente la celda `df.Revenue (Millions)` porque era solo un ejemplo de lo que podía salir mal
      - Ademas de que si la dejas así ya no corren las demas celdas.

### Subit a repo (gitHub)

1. `git status` se debe ver el .ipynv modificado y lo que mas modificaste o agregaste.
2. `git add .` o `git add -A` si quieres asegurarte de guardar cada cambio en cualquier parte del proyecto
3. `git commit -m "Ejecuto notebook, guardo outputs y modifico README.md con lo que hice"`
4. `git push origin main` sube los cambios a gitHub en la rama main (debimos haber creado otra rama y despues hacer merge)
