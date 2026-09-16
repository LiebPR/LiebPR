# Alejandro PR | Unity & C# Game Developer

Especializado en **Arquitectura Limpia**, **Principios SOLID** y **Optimización de Rendimiento** para desarrollo en Unity. Enfocado en construir sistemas modulares y desacoplados utilizando **Inyección de Dependencias** basada en interfaces y **Comunicación por Eventos**.

---

### 🛠️ Competencias Técnicas & Arquitectura

* **Motor y Lenguaje:** Unity 2D / 3D | C#
* **Arquitectura y Patrones:** Principios SOLID | Inyección de Dependencias | Comunicación por Eventos | FSM | Object Pooling
* **Rendimiento y Memoria:** Control del Ciclo de Vida | Gestión del Garbage Collector | Bucle Centralizado de Ticks (`ITickable`, `IFixedTickable`) | Arquitectura con Clases Puras de C#
* **Flujo de Trabajo:** Git | GitHub Desktop | PowerShell

---

### 🎮 Proyectos

#### **Dead Live** — *Horde Survival 2.5D (Cel-Shaded)*
* **Reto Técnico:** Optimización de FPS y prevención de picos del Garbage Collector frente a hordas masivas de enemigos.
* **Arquitectura:** Sustitución de `MonoBehaviours` pesados por **clases puras de C#** para gestionar las entidades, reduciendo drásticamente la sobrecarga de memoria.
* **Control de Ciclo de Vida:** Centralización del flujo de ejecución mediante un gestor central con interfaces `ITickable` y `IFixedTickable`, respaldado por **Object Pooling** y **Máquinas de Estados (FSM)**.

#### **Burden Of Choices** — *Puzzles y Narrativa 3D*
* **Reto Técnico:** Control de físicas interactivo y gestión dinámica de IA enemiga.
* **Sistemas:** Implementación de mecánicas de físicas aplicadas a la resolución de acertijos y control de comportamiento/rutas de enemigos mediante **Unity NavMesh**.
