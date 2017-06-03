# polymer-Workshop

Repositorio con el código a desarrollar a lo largo del seminario hands-on sobre WebComponents & Polymer

---

## Para lanzar webComponentStandard

- Abrir una terminal dentro de una carpeta con un archivo index.html
- Ejecutar dependiendo de la versión de python:
  - Python2 `python -m SimpleHTTPServer`
  - Python3 `python3 -m http.server`
- Abrir un navegador y acceder a la ruta `localhost:[PUERTO]` donde el puerto será el que esté escuchando el servidor de python creado en el paso anterior. *(En el paso anterior veremos por consola el puerto)*

---

## Polymer

##### Setup
- Instalar **Git**
- Instalar **Node6** o superior
- Ejecutar `npm install -g bower` para instalar **bower** a nivel global
- Ejecutar `npm install -g polymer-cli` para instalar **polymer-cli** a nivel global *(Command Line Interface)*

##### Crear componente de cero
- `polymer init`

##### Servir un componente
- `polymer serve --open`

##### Acceder a la demo del componente
- Navegar a la url `http://localhost:8080/components/custom-component/demo/index.html`
