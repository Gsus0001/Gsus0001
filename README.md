
<div align="center">
  
  ![Typing SVG](https://readme-typing-svg.demolab.com?font=Bodoni+Moda&size=35&pause=1000&color=44FF44&background=0D1117&center=true&vCenter=true&width=630&height=80&lines=Jesus+D.+Perez;El+aprendizaje+nunca+agota+la+mente.)

 ## $ TERMINAL v1.0 | MODO BUROCRATA ACTIVADO
  </div>


## `$ whoami`
```bash
> Usuario: Gsus0001
> Expediente: EST-2026-001
> Estado: EN FORMACIÓN ACTIVA
> Institución: UTN - UTN/FRD
> Ubicación: /home/gsus/aprendiendo
> Shell: /bin/bash (con mucho sudo)
```

---
## 📄 'Expediente Personal' 

***"Estudio programación en la UTN, ciberseguridad, adm. de servidores e trabajo, y entre clase y clase, me la paso rompiendo cosas en Linux y tratando de entender por qué Git tiene tantos comandos. No soy developer (todavía), pero soy al que le gusta intentar, reinstalar y volver a intentar."***

---
## 🤖 `EL BUROCRATA DE GIT`

***$ "Git no es difícil. Solo tiene 150 comandos con 3 flags cada uno, 4 áreas internas, 3 estados posibles por archivo, y 5 maneras de hacer lo mismo. Pero fuera de eso, es sencillo."***

***$ "¿Qué querés hacer un commit rápido? Primero llená el formulario ADD, después el COMMIT, y si no ponés mensaje, te lo rechazo."*** 

<p align="center">
  <img src="https://img.shields.io/badge/📄_EXPEDIENTE_GIT-ACTIVO-0F0?style=flat-square&labelColor=0D0D0D&color=0F0" />
  <img src="https://img.shields.io/badge/🕹️_RAMA_-_main__%2F__master-0F0?style=flat-square&labelColor=0D0D0D&color=0F0" />
  <img src="https://img.shields.io/badge/🔒_PULL_REQUEST-REVISIÓN_PENDIENTE-0F0?style=flat-square&labelColor=0D0D0D&color=0F0" />
</p>

---

## 🤖 `Simulador del Burócrata de Git`

```python
"""
Burócrata de Git - Sistema de Gestión de Expedientes
"""

class DepartamentoGit:
    """El burócrata más temido del control de versiones"""
    
    def __init__(self, expediente="EXP-001"):
        self.expediente = expediente
        self.estado = "EN REVISIÓN"
        self.historial = []
        self.aprobados = 0
        self.rechazados = 0
    
    def revisar_commit(self, mensaje):
        """¿Tu mensaje es lo suficientemente bueno para el burócrata?"""
        if len(mensaje) < 10:
            self.rechazados += 1
            self.estado = f"RECHAZADO ({self.rechazados} errores)"
            return "❌ RECHAZADO: Describe mejor tu commit, plebe."
        
        self.aprobados += 1
        self.historial.append(mensaje)
        self.estado = f"APROBADO ({self.aprobados} commits felices)"
        return f"✅ APROBADO: El burócrata sonríe."
    
    def __str__(self):
        """El cartel que reemplaza al estático"""
        return f"""
┌────────────────────────────────────────────────────────────────────┐
│ EXPEDIENTE: {self.expediente:<13}                                  │
│ ESTADO: {self.estado:<22}                                          │
│ COMMITS: {self.aprobados} ✅  {self.rechazados} ❌                │
│ ÚLTIMO: {self.historial[-1][:18] if self.historial else 'Ninguno'} │
└────────────────────────────────────────────────────────────────────┘
"""
```
![Estado del Expediente](https://img.shields.io/badge/EXPEDIENTE-APROBADO-brightgreen)

<div align="center"><br>

  ***🖨️ Este perfil fue revisado, sellado y aprobado por el Departamento de Burocracia de Git***
  
  `N° de expediente: GIT-2026-001 | Fecha de emisión: Hoy | Validez: Hasta el próximo commit --force`

</div><br>

## 👁️ `Accesos Registrados:`

![Visitas](https://komarev.com/ghpvc/?username=Gsus0001&color=green&style=flat-square&label=ACCESOS)


<p align="center"> <img src="https://img.shields.io/badge/📄_EXPEDIENTE-ACTIVO-00FF00?style=flat-square&labelColor=0D0D0D&color=00FF00" /> <img src="https://img.shields.io/badge/🎓_UTN-EN_CURSO-00FF00?style=flat-square&labelColor=0D0D0D&color=00FF00" /> <img src="https://img.shields.io/badge/🐧_LINUX-EXPLORANDO-00FF00?style=flat-square&labelColor=0D0D0D&color=00FF00" /> <img src="https://img.shields.io/badge/📦_GIT-APRENDIENDO-00FF00?style=flat-square&labelColor=0D0D0D&color=00FF00" /> </p>
