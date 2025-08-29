# Vue 3 + Vite

This template should help get you started developing with Vue 3 in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

Learn more about IDE Support for Vue in the [Vue Docs Scaling up Guide](https://vuejs.org/guide/scaling-up/tooling.html#ide-support).

🗓️ Proyecto actualizado el dia 20250829 a las 1:12 pm Colombia

©️ Autor: Luis Hernando Murcia Amortegui

📧 Contacto: luisamortegui.3691@gmail.com


🚀 Submit de formularios y Events Modifiers

Se añaden las propiedades faltantes al objeto, se habilita la herramienta de Google Vue.js devtools para poder depurar la información que se almacena en nuestro objeto gracias a la librería de reactive de Vue.js

Lo que normalmente se veria con JavaScript

const formulario = document.querySelector('#id');
formulario = addEventListener('submit', function(e){
    // logica
    e.preventDefault():
});

Con Vue.js, solo de ingresamos la directiva de eventos @submit-prevent="[nombre_variable]" algo mas sencillo y util 

✅ Se evidencia el mensaje en consola una vez se da clic en el boton.

![Vista](docs/images/imagen.png)





