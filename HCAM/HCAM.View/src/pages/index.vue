<template>
  <q-page class="flex flex-center">
    <img alt="Quasar logo" src="~assets/quasar-logo-full.svg">
<q-btn icon="map" to="/Account"/>
    <span>To Accounting</span>
    <router-link to="/Account">User</router-link>


    <router-link to="accountType">
      <q-btn icon="send" />
    </router-link>

  </q-page>
</template>

<style>
</style>

<script>
export default {
  name: 'PageIndex'
}
</script>
