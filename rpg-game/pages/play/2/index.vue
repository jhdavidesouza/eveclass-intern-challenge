<template>
    <v-main>
        <v-card-text>
            <h1>Fase 2</h1>
            <p>
                Ao ver que a manada passou, você desce da árvore e começa a explorar a região
                em busca de respostas. Não muito distante dali, você encontra um acampamento
                abandonado e um bilhete com instruções, deixado para trás. Antes que você possa
                alcançar o bilhete, um homem aparece com uma marreta gritando e avançando em
                sua direção. No seu corpo a adrenalina dispara. O que você faz?
            </p>
        </v-card-text>
        <v-btn class="opcao" to="/play/2/outcome/1">
            a. Foge para bem longe
        </v-btn>
        <br>
        <v-btn class="opcao" to="/play/2/outcome/2">
            b. Pega o bilhete e foge para bem longe
        </v-btn>
        <br>
        <v-btn class="opcao" to="/play/2/outcome/3">
            c. Puxa toda coragem do coração e enfrenta o homem
        </v-btn>
        <hr class="my-3">
        <v-btn to="/play/1/outcome/2">
            VOLTAR PARA OPÇÃO ANTERIOR
        </v-btn>
        <v-btn to="/">
            VOLTAR AO INÍCIO
        </v-btn>
    </v-main>
</template>

<script>
    
</script>

<style scoped>
    
</style>