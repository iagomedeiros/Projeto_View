<template>
    <div class="box">
        <div class="columns">
            <div class="column is-8" role="form" aria-label="Formulário para criação de uma nova tarefa ">
                <input type="text" class="input" placeholder="Qual a tarefa você deseja iniciar?">
            </div>
            <div class="column">
            <Temporizador/>    

            </div>
        </div>
    </div>
</template>

<script lang="ts">
import { defineComponent, DefineComponent } from 'vue';
import Temporizador from './Temporizador.vue'

export default defineComponent({
    name: "Formulário-nome",
    components:{
        Temporizador
    }
})
</script>