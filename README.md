#Estructuras de Datos: Implementación de Árboles en C++ y Java

Este repositorio contiene la implementación y el análisis de cinco ejercicios fundamentales sobre estructuras de datos jerárquicas: **Árboles N-arios** y **Árboles Binarios de Búsqueda (BST)**.

El proyecto fue desarrollado de forma paralela en **C++** y **Java**, permitiendo comparar las diferencias en sintaxis, manejo de memoria y estructuras dinámicas entre ambos lenguajes.

---

# Contenido del Proyecto

El proyecto se divide en cinco módulos prácticos que abordan distintos desafíos algorítmicos relacionados con árboles.

## Ejercicios Implementados

### Conteo de Nodos (Árbol N-ario)
Implementación recursiva para contabilizar todos los nodos de una estructura con múltiples hijos.

### Inserción en BST
Inserción de nodos respetando la propiedad:
- menores → subárbol izquierdo
- mayores o iguales → subárbol derecho

### Cálculo de Altura
Determinación del nivel máximo de profundidad del árbol utilizando recursividad.

### Recorrido In-Order
Visita de nodos en el orden:
```text
Izquierda → Raíz → Derecha
````
# Estructura del proyecto
````
APE-ARBOLES/                       
├── APE3_ARBOLES/              
│   ├── .vscode/                    
│   │   └── settings.json
│   ├── APE_Arboles/  
│   │   ├── cpp/                 
│   │   │   ├── Ejercicio1_Basico.cpp
│   │   │   ├── Ejercicio2_Binario.cpp
│   │   │   ├── Ejercicio3_Binario.cpp
│   │   │   ├── Ejercicio4_Recorridos.cpp
│   │   │   ├── Ejercicio5_Transformacion.cpp
│   │   │   ├── ejercicio1.exe
│   │   │   ├── ejercicio2.exe
│   │   │   ├── ejercicio3.exe
│   │   │   ├── ejercicio4.exe
│   │   │   └── ejercicio5.exe
│   │   └── java/                
│   │       ├── Ejercicio1_Basico.java
│   │       ├── Ejercicio1_Basico.class
│   │       ├── Ejercicio2_Binario.java
│   │       ├── Ejercicio2_Binario.class
│   │       ├── Ejercicio3_Binario2.java
│   │       ├── Ejercicio3_Binario2.class
│   │       ├── Ejercicio5_Transformacion.java
│   │       ├── Ejercicio5_Transformacion.class
│   │       ├── RecorridoInOrder.java
│   │       ├── RecorridoInOrder.class
│   │       ├── Nodo.class  
│   │       └── NodoN.class        
│   └── README.md                   
├── INFORME_APE3.pdf            
└── README.md                       

````
# Ejecución
* C++
cd  /APE3_ARBOLES/APE_Arboles/cpp
g++ [name:Ejercico].cpp -o [name:Ejercicio]
./[name:Ejercicio]

* Java
cd  /APE3_ARBOLES/APE_Arboles/java
javac [name:Ejercico].java
java [name:Ejercico]



