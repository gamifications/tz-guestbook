<template>
  <v-app dark>
   
    <v-alert
      border="bottom"
      color="green"
      dark
    >
      <h1>Tezos Tweet</h1> 
     The data is stored in a <a style="color: #ccc" about="_blank" href="https://better-call.dev/mainnet/KT1D44p6zaTi5T4WCn7u5vmmapHGR1HXz1F8/operations">smart contract</a> on the mainnet.
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
</style>
