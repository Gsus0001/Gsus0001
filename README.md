
<div align="center">
  
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=500&color=0F0&background=0D0D0D&center=true&vCenter=true&width=440&lines=G+S+U+S+0+0+0+1;TERMINAL+MATRIX+v1.0;MODO+BUROCRATA+ACTIVADO" alt="Typing SVG" />
  
</div>

---

## `$ whoami`

```bash
> Gsus0001
> Perfil: Obsesivo del orden | Amante de la burocracia de Git | Hacker por hobbie
```

## `$ pwd`
/home/gsus/repositorios

## $ `uptime --pretty`
Commit activo | Sistema estable | Modo: enfoque total

## 📊 Estadísticas

https://github-readme-stats.vercel.app/api?username=Gsus0001&show_icons=true&theme=dark&hide_title=true&bg_color=0D0D0D&title_color=0F0&text_color=0F0&icon_color=0F0

https://streak-stats.demolab.com?user=Gsus0001&theme=dark&hide_border=true&background=0D0D0D&stroke=0F0&ring=0F0&fire=0F0&currStreakNum=0F0&sideNums=0F0&currStreakLabel=0F0&sideLabels=0F0&dates=0F0

https://github-readme-stats.vercel.app/api/top-langs/?username=Gsus0001&layout=compact&theme=dark&bg_color=0D0D0D&title_color=0F0&text_color=0F0

# 📁 Proyectos Activos

> `Repositorios                  Descripción`
> Tecnicatura_2026                Aprendizaje Constante
> Python_Final                    Proyecto en evolucion
> Gsus0001                        Mi perfil

🤖 EL BUROCRATA DE GIT

> "Git no es difícil. Solo tiene 150 comandos con 3 flags cada uno, 4 áreas internas, 3 estados posibles por archivo, y 5 maneras de hacer lo mismo. Pero fuera de eso, es sencillo."

> "¿Que querés hacer un commit rápido? Primero llená el formulario ADD, después el COMMIT, y si no ponés mensaje, te lo rechazo."

# app.py

from flask import Flask, render_template, request, redirect, url_for
from utils import obtener_datos, procesar_datos
from db import conectar

app = Flask(__name__)

@app.route('/')
def index():
    datos = obtener_datos()
    return render_template('index.html', datos=datos)

@app.route('/agregar', methods=['POST'])
def agregar():
    nombre = request.form['nombre']
    valor = request.form['valor']
    conexion = conectar()
    cursor = conexion.cursor()
    cursor.execute('INSERT INTO datos (nombre, valor) VALUES (%s, %s)', (nombre, valor))
    conexion.commit()
    return redirect(url_for('index'))

# Más código abajo...

def procesar():
    datos = obtener_datos()
    resultado = procesar_datos(datos)
    return resultado

🟢 Estado: Operativo 
📅 Última conexión: Hoy
👁️ ACCESOS REGISTRADOS:
https://komarev.com/ghpvc/?username=Gsus0001&color=0F0&style=flat-square&label=ACCESOS












