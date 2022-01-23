<template>
    <v-main>
        <v-card-text>
            <h1>Fase 3</h1>
            <p>
                Você finalmente consegue ler o bilhete: “Vamos fazer parecer um acidente. Misture o
                conteúdo deste frasco na comida dele. O remédio vai começar a fazer efeito depois
                de 30 minutos. Quando ele estiver completamente apagado, leve-o até o pé da
                árvore mais alta no início da floresta e direcione a manada de búfalos em sua
                direção. Estaremos esperando no laboratório ao norte do acampamento.” O que
                você faz?
            </p>
        </v-card-text>
        <v-btn class="opcao" to="/play/3/outcome/1">
            a. Foge e liga para a polícia
        </v-btn>
        <br>
        <v-btn class="opcao" to="/play/3/outcome/2">
            b. Amarra o homem e vai ao laboratório
        </v-btn>
        <br>
        <v-btn class="opcao" to="/play/3/outcome/3">
            c. Mata o homem, pega a marreta e vai ao laboratório
        </v-btn>
        <hr class="my-3">
        <v-btn to="/play/2/outcome/3">
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