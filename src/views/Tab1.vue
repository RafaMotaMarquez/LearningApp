<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Pass</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">QR code</ion-title>
        </ion-toolbar>
      </ion-header>
      <div>
        <ion-button color="primary">Primary</ion-button>
        <ion-button color="secondary">Secondary</ion-button>
        <ion-button color="tertiary">Tertiary</ion-button>
        <ion-button color="success">Success</ion-button>
        <ion-button color="warning">Warning</ion-button>
        <ion-button color="danger">Danger</ion-button>
        <ion-button color="light">Light</ion-button>
        <ion-button color="medium">Medium</ion-button>
        <ion-button color="dark">Dark</ion-button>
      </div>
       <ion-badge>99</ion-badge>

  <!-- Colors -->
  <ion-badge color="primary">11</ion-badge>
  <ion-badge color="secondary">22</ion-badge>
  <ion-badge color="tertiary">33</ion-badge>
  <ion-badge color="success">44</ion-badge>
  <ion-badge color="warning">55</ion-badge>
  <ion-badge color="danger">66</ion-badge>
  <ion-badge color="light">77</ion-badge>
  <ion-badge color="medium">88</ion-badge>
  <ion-badge color="dark">99</ion-badge>

  <!-- Item with badge on left and right -->
  <ion-item>
    <ion-badge slot="start">11</ion-badge>
    <ion-label>My Item</ion-label>
    <ion-badge slot="end">22</ion-badge>
  </ion-item>

      <ExploreContainer name="Tab 1 page" />
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
import ExploreContainer from "@/components/ExploreContainer.vue";

export default {
  name: "Tab1",
  components: {
    ExploreContainer,
    IonHeader,
    IonToolbar,
    IonTitle,
    IonContent,
    IonPage,
  },
};
</script>