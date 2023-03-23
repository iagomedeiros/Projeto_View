<template>
    <div class="box has-text-weight-bold">
        <div class="columns">
            <div class="columns is-7">Descrição da Tarefa</div>
            <div class="column"> <Cronometro tempoEmSeundos="15"/> </div>
        </div>
    </div>
</template>

<script lang="ts">
import { traverseFast } from '@babel/types';
import { defineComponent, DefineComponent } from 'vue';
import Cronometro from './Cronometro.vue';

export default defineComponent({
    name: 'Tarefa-anotar',
    components:{
        Cronometro ,
    }
})
</script>

<style>
.box{
    background: #FAF0CA;
}
</style>