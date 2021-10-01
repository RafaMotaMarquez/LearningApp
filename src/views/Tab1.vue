<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Liste cryptos</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
<!-- List of cryptos -->
      <ion-list>
        <ion-item>
       
          <ion-label> <a href="https://coinmarketcap.com/fr/currencies/bitcoin/">Bitcoin</a></ion-label>
        </ion-item>
        <ion-item>
          <ion-label>VET</ion-label>
        </ion-item>
        <ion-item>
          <ion-label>VTHO</ion-label>
        </ion-item>
        <ion-item>
          <ion-label>ETH</ion-label>
        </ion-item>
      </ion-list>

  <!-- List of Input Items -->
 
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import {
  IonPage,
  IonHeader,
  IonToolbar,
  IonTitle,
  IonContent,
} from "@ionic/vue";

export default {
  name: "Tab1",
  components: {

    IonHeader,
    IonToolbar,
    IonTitle,
    IonContent,
    IonPage,
  },
};
</script>