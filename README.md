# 🎲 Proyecto: Juego de Dados en Android

Este proyecto es una sencilla aplicación de Android que simula el lanzamiento de dos dados. Está diseñado con Java y utiliza un enfoque interactivo para generar resultados aleatorios, proporcionando una experiencia divertida y visual.

## 🚀 Funcionalidades

- **Lanzamiento de Dados**: Al presionar el botón del cubilete, se lanzan dos dados que muestran resultados aleatorios.
- **Verificación de Coincidencia**: 
  - Si los dados coinciden en el número, se muestra un mensaje: `¡ENHORABUENA, los dados han coincidido!`.
  - Si no coinciden, el mensaje será: `¡Lo siento, fallaste!`.
- **Interfaz Visual**: Las imágenes de las caras de los dados cambian dinámicamente según el resultado del lanzamiento.
- **Feedback Instantáneo**: Los mensajes se muestran utilizando *Toast*, ofreciendo una respuesta rápida y visual al usuario.

## 🛠️ Tecnologías Utilizadas

- **Lenguaje**: Java
- **Entorno de Desarrollo**: Android Studio
- **Componentes de la Interfaz**:
  - `ImageButton`: Para activar el lanzamiento de los dados.
  - `ImageView`: Para mostrar las caras de los dados.
  - `Toast`: Para mostrar los mensajes de resultado.

## 📋 Cómo Funciona

1. Se definen las imágenes de las caras de los dados en un `ArrayList`.
2. Al presionar el botón, se generan dos números aleatorios (uno para cada dado) utilizando la clase `Random`.
3. Las caras correspondientes a los números generados se asignan a las vistas de los dados (`ImageView`).
4. Se verifica si los números generados coinciden:
   - Si coinciden, se muestra un mensaje de éxito.
   - Si no coinciden, se muestra un mensaje de fallo.

## 🎯 Capturas de Pantalla
![image](https://github.com/user-attachments/assets/9a3f459e-851d-45c7-8dfd-5a4f846b1881)
![image](https://github.com/user-attachments/assets/8e5c754e-8070-47bb-988c-4c0fdc175350)



## 📂 Estructura del Proyecto

```plaintext
📁 app
 ├── 📁 res
 │    ├── 📁 drawable
 │    │    ├── cara1.png
 │    │    ├── cara2.png
 │    │    ├── cara3.png
 │    │    ├── cara4.png
 │    │    ├── cara5.png
 │    │    └── cara6.png
 │    ├── 📁 layout
 │    │    └── activity_main.xml
 ├── 📁 java
 │    └── com.example.dados
 │         └── MainActivity.java
