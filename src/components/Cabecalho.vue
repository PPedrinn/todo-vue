<script setup>
    const props = defineProps(['tarfasPendentes'])
</script>

<template>
        <header class="p-5 mb-4 mt-4 bg-light rounded-3">
        <h1>Minhas tarefas</h1>
        <p>
            Você possui {{ props.tarfasPendentes }} tarefas pendentes
        </p>
    </header>
</template>