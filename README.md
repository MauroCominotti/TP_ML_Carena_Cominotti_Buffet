# TP_ML_Carena_Cominotti_Buffet
UCSE Machine Learning TP N°1

## Instalación y configuración del proyecto
Probar que las lineas que pasaron los profes den todas OK
1. Descargar e instalar virtualbox
2. Descargar la última versión de Ubuntu
3. Crear una nueva VM en Virtualbox, indicarle a la vm que vas a instalar linux y la versión (ubuntu)
4. Va a pedir seleccionar cómo vas a bootear el sistema, selecciona la imagen del ubuntu que descargaste
5. Darle a todo siguiente, instalar ubuntu, siguiente siguiente
6. Crear una carpeta en **Documentos**, ponerle de nombre Jupyter si se quiere
7. Abrir un terminal e ingresar a esa carpeta, luego tipear éstos comandos:
```bash
$ sudo apt install python3-pip

$ pip install jupyter[notebook] pandas numpy matplotlib seaborn plotly scikit-learn keras tensorflow h5py pillow sklearn-pandas --user
```
8. Finalmente abrir el jupyter con: 
```bash
jupyter notebook

# Si no funciona ese comando colocar 
python3 -m notebook
```
