<script setup>

import medias from "@images/avatars/medias.jpg";
import medias2 from "@images/avatars/medias2.jpg";
import medias3 from "@images/avatars/medias3.jpg";
const handleClick = () => {
  // Lógica a ejecutar cuando se hace clic en el avatar
  console.log("Clic en el avatar");
};
</script>

<template>
  <VRow class="ma-1">
    <VCol cols="12" sm="6" md="4" lg="2" class="text-center">
      <VCard @click="handleClick">
        <VImg :src="medias" />
        <VCardText style="font-size: 18px;">Medias</VCardText>
      </VCard>
    </VCol>
    <VCol cols="12" sm="6" md="4" lg="2" class="text-center">
      <VCard @click="handleClick">
        <VImg :src="medias2" />
        <VCardText style="font-size: 18px;">Medias</VCardText>
      </VCard>
    </VCol>
    <VCol cols="12" sm="6" md="4" lg="2" class="text-center">
      <VCard @click="handleClick">
        <VImg :src="medias3" />
        <VCardText style="font-size: 18px;">Medias</VCardText>
      </VCard>
    </VCol>
    <VCol cols="12" sm="6" md="4" lg="2" class="text-center">
      <VCard @click="handleClick">
        <VImg :src="medias" />
        <VCardText style="font-size: 18px;">Medias</VCardText>
      </VCard>
    </VCol>
    <VCol cols="12" sm="6" md="4" lg="2" class="text-center">
      <VCard @click="handleClick">
        <VImg :src="medias2" />
        <VCardText style="font-size: 18px;">Medias</VCardText>
      </VCard>
    </VCol>
    <VCol cols="12" sm="6" md="4" lg="2" class="text-center">
      <VCard @click="handleClick">
        <VImg :src="medias" />
        <VCardText style="font-size: 18px;">Medias</VCardText>
      </VCard>
    </VCol>
    <VCol cols="12" sm="6" md="4" lg="2" class="text-center">
      <VCard @click="handleClick">
        <VImg :src="medias2" />
        <VCardText style="font-size: 18px;">Medias</VCardText>
      </VCard>
    </VCol>
    <VCol cols="12" sm="6" md="4" lg="2" class="text-center">
      <VCard @click="handleClick">
        <VImg :src="medias3" />
        <VCardText style="font-size: 18px;">Medias</VCardText>
      </VCard>
    </VCol>
    <VCol cols="12" sm="6" md="4" lg="2" class="text-center">
      <VCard @click="handleClick">
        <VImg :src="medias" />
        <VCardText style="font-size: 18px;">Medias</VCardText>
      </VCard>
    </VCol>
    <VCol cols="12" sm="6" md="4" lg="2" class="text-center">
      <VCard @click="handleClick">
        <VImg :src="medias2" />
        <VCardText style="font-size: 18px;">Medias</VCardText>
      </VCard>
    </VCol>
    <VCol cols="12" sm="6" md="4" lg="2" class="text-center">
      <VCard @click="handleClick">
        <VImg :src="medias3" />
        <VCardText style="font-size: 18px;">Medias</VCardText>
      </VCard>
    </VCol>
  </VRow>
</template>
