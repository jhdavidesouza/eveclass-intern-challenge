<template>
    <v-main>
        <v-card-text>
            <h1>Fase 1</h1>
            <p>
                Você acordou na floresta tonto e com uma grande dor de cabeça, sem nenhuma
                memória de como foi parar ali. Um barulho cada vez mais intenso foi o que
                despertou você desse apagão. Após abrir os olhos e levantar-se, você observa uma
                manada de búfalos vindo em sua direção, a pouquíssimos metros de distância. O
                que você faz?
            </p>
        </v-card-text>
        <v-btn class="opcao" to="/play/1/outcome/1">
            a. Corre o mais rápido possível 
        </v-btn>
        <br>
        <v-btn class="opcao" to="/play/1/outcome/2">
            b. Sobe na árvore
        </v-btn>
        <br>
        <v-btn class="opcao" to="/play/1/outcome/3">
            c. Se finge de morto
        </v-btn>
        <hr class="my-3">
        <v-btn to="/">
            VOLTAR AO INÍCIO
        </v-btn>
    </v-main>
</template>

<script>
    
</script>

<style scoped>
    
</style>