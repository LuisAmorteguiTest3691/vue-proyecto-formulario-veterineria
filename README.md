# Vue 3 + Vite

This template should help get you started developing with Vue 3 in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

Learn more about IDE Support for Vue in the [Vue Docs Scaling up Guide](https://vuejs.org/guide/scaling-up/tooling.html#ide-support).

🗓️ Proyecto actualizado el dia 20250829 a las 1:12 pm Colombia

©️ Autor: Luis Hernando Murcia Amortegui

📧 Contacto: luisamortegui.3691@gmail.com


🚀 Renderizando el componente Alerta 

Para renderizar utilizamos la directiva de vue v-if="[objeto.propiedad]" para poder establecer si viene con valores, tambien se asigna el nombre del props en el componente formularios llamado :alerta, asignando el obejeto alerta. 

Una vez se ha nombrado el props en el componente formulario, se crea el objeto props de tipo defineProps

<script setup>
    const props = defineProps({
        alerta: {
            type: Object,
            required: true
        }
    });
</script>

con esto definimos el valor de nuestro props podemos tomar los valores de nuestro objeto.

<template>
    <div class="text-white text-center p-3 uppercase font-bold mb-3 rounded-md bg-red-400"> 
        {{ alerta.mensaje }}
    </div>
</template>


✅ Vista

![Vista](docs/images/imagen.png)





