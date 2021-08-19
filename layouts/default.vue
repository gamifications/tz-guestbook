<template>
  <v-app dark>
   
    <v-alert
      border="bottom"
      color="red"
      dark
    >
      <h1>Tezos Tweet:  Florencenet (testnet)</h1> 
     The data is stored in a <a about="_blank" href="https://better-call.dev/florencenet/KT1QoBbDa9W6DJKbbAucoMdhNtFjdjvEGPqo/operations">smart contract</a> on the testnet. The testnet can be reset any time, so this data will likely get lost.
    </v-alert>
    <v-main>
      <v-container>
        <nuxt />
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
export default {
  data () {
    return {
    }
  }
}
</script>

<style>
  .link {
    text-decoration: none;
  }
  a {
    color: #ccc;
  }
</style>
