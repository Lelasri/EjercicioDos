  GNU nano 4.9                              readme.md

# Segundo ejercicio

 1. **¿Cómo tienes instalado Python?** Podéis acompañarlo de la salida de `which python`, `which python3`, `python --version`, `python3 --version` 

- En la terminal tengo instalada la versión Python 2.7.18. He obtenido esta respuesta poniendo en mi terminal: `$ python --version`. No tengo instalado Python 3 porque me dio error desde el principio. 

- Cuando busco en mi terminal Python 3 haciendo lo siguiente: `$ which python3`, me da este resultado: `which: no python3 in (/usr/local/bin:/usr/bin:/cygdrive/c/Program Files (x86)/Common Files/Oracle/Java/javapath:/cygdrive/c/Windows/system32:/cygdrive/c/Windows:/cygdrive/c/Windows/System32/Wbem:/cygdrive/c/Windows/System32/WindowsPowerShell/v1.0:/cygdrive/c/Windows/System32/OpenSSH:/cygdrive/c/Users/Lenovo/AppData/Local/Microsoft/WindowsApps)`

2. **¿Tienes Anaconda? ¿Lo usas fuera del máster o/y en el máster?** Puedes acompañarlo de `echo $PATH` 
- Por el momento solo utilizo Anaconda en el máster. 

3. **¿Ejecutas Python desde la terminal?** Con la salida de `which` hazle un `ls -la` a esa ruta. Aquí me interesa saber si ejecutas Jupyter desde la terminal, desde la aplicación gráfica de Anaconda o cómo. 

- Cuando hago `which python` y `ls -la` el resultado que obtengo relativo a Python es el siguiente:

    drwx------+ 1 Lenovo Ninguno       0 Nov 30 20:44  .ipython
    drwx------+ 1 Lenovo Ninguno       0 Nov 30 20:38  .jupyter


- No suelo ejecutar Python desde la terminal. Utilizo Python con Anaconda Navigator y Jupyter. Tampoco ejecuto Jupyter desde la terminal, sino desde la aplicación gráfica de Anaconda. 

4. **¿Usas Collab? ¿Solo collab o como una aplicación de terceros más?**

- Creo que no. 

5. **¿Sabes que es pip?** Puedes acompañarlo de `pip --version` y `pip3 --version`, `which pip` y `which pip3`. Por cierto que en mi GNU/Linux me dice que ``which`está depreciado, que use `command -v``, es decir, `command -v pip`, etc. 6. ¿Usas pip, condas u otro método?

- Pip es un gestor de paquetes de Python. Lo utilizamos en clase del profesor Martín Nadal para instalar folium, una librería de mapas interactivos, de la siguiente forma: `!pip install folium`. Solo he utilizado pip a través de la aplicación gráfica de Anaconda. 
