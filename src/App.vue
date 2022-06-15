<script>
import MenuLateral from "@/components/MenuLateral.vue";
import Rodape from "@/components/FooterRodape.vue";
import Conteudo from "@/components/ConteudoMenu.vue";
import Cabecalho from "@/components/HeaderCabeçalho.vue";
export default {
  components: { MenuLateral, Rodape, Conteudo, Cabecalho },
};
</script>

<template>
  <MenuLateral />
  <Cabecalho />
  <Rodape />
  <Conteudo />
</template>

<style></style>