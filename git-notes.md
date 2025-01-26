### 1. `git init` 🚀 
Inicializa un repositorio Git en la carpeta actual. Sirve para convertir una carpeta en un repositorio donde podrás versionar tus cambios.

### 2. `git add` ➕ 
Agrega archivos al área de preparación (stage). Esto significa que estás diciendo a Git qué archivos quieres incluir en el próximo commit.

**Ejemplo:** 
```bash  
$ git add archivo.txt
```

### 3. `git commit -m` "[mensaje]" 📜

Guarda los cambios en el historial de tu repositorio con un mensaje descriptivo.

Es como tomar una “foto” del estado actual de tus archivos.

**Ejemplo:**
```bash
 $ git commit -m "Añadí el archivo index.html"
   ``` 
### 4. `git status` 🔍

Muestra el estado del repositorio:

Qué archivos han sido modificados.
Cuáles están en el área de preparación.
Si hay algo listo para ser guardado con un commit.

**Ejemplo:**
```bash
 $ git status
```    
### 5. `git log` 📚

Muestra el historial de commits realizados en tu repositorio.

Es útil para ver qué cambios se hicieron y cuándo.

**Ejemplo:**
```bash
 $ git log
```    
### 6. `git push` ⬆️

Sube tus cambios del repositorio local al repositorio remoto (por ejemplo, GitHub).

**Ejemplo:**
```bash
 $ git push origin main
```    
### 7.`git clone` [URL] 📥

Crea una copia exacta de un repositorio remoto en tu máquina local.

**Ejemplo:**
```bash
 $ git clone https://github.com/usuario/repositorio.git
 ```