<template>
  <v-container>
    <v-card elevation="2" outlined>
      <v-card-title>Mon super titre</v-card-title>
      <v-card-text>Plein de textes !!!!</v-card-text>
      <v-card-action>
        <v-btn>Bouton</v-btn>
      </v-card-action>
    </v-card>
    <v-btn color="success" :to="{name: 'Home'}">Home</v-btn>
  </v-container>
</template>
