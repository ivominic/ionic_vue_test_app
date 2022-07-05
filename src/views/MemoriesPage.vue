<template>
  <base-layout page-title="All memories">
    <ion-list>
      <ion-item router-link="/memories/1">First</ion-item>
      <ion-item router-link="/memories/2">Second</ion-item>
      <ion-item router-link="/memories/3">Third</ion-item>
    </ion-list>
  </base-layout>
</template>

<script>
import { IonList, IonItem } from "@ionic/vue";
export default {
  components: {
    IonList,
    IonItem,
  },
};
</script>
