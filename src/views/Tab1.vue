<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>List des cryptos</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <!-- List of cryptos -->
      <ion-list>
        <ion-item>
          <ion-label>
            <a
              href="https://coinmarketcap.com/fr/currencies/bitcoin/"
              target="_blank"
              >BITCOIN</a
            >
          </ion-label>
        </ion-item>
           <ion-item>
          <ion-label>
            <a
              href="https://coinmarketcap.com/fr/currencies/ethereum/"
              target="_blank"
              >ETHERUM</a
            >
          </ion-label>
        </ion-item>
        <ion-item>
          <ion-label>
            <a
              href="https://coinmarketcap.com/fr/currencies/vechain/"
              target="_blank"
              >VET</a
            >
          </ion-label>
        </ion-item>
             <ion-item>
          <ion-label>
            <a
              href="https://coinmarketcap.com/fr/currencies/vethor-token/"
              target="_blank"
              >VTHO</a
            >
            </ion-label>
            </ion-item>
             <ion-item>
          <ion-label>
            <a
              href="https://coinmarketcap.com/fr/currencies/enjin-coin/"
              target="_blank"
              >ENJ</a
            >
            </ion-label>
        </ion-item>
          <ion-item>
          <ion-label>
            <a
              href="https://coinmarketcap.com/fr/currencies/cardano/"
              target="_blank"
              >ADA</a
            >
            </ion-label>
        </ion-item>
                 <ion-item>
          <ion-label>
            <a
              href="https://coinmarketcap.com/fr/currencies/polygon/"
              target="_blank"
              >MATIC</a
            >
            </ion-label>
        </ion-item>
      </ion-list>
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