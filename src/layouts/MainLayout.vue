
<template>
  <q-layout view="hHh lpR fFf">

                <link href="../css/styles.css" rel="stylesheet" />

    <q-header elevated class="bg-dark text-white flex flex-center">



                  <q-title class="q-pa-md">

                       Nft Portfolio (by Musayasin) 

                  </q-title>



    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>

  </q-layout>
</template>


<script>
import { defineComponent } from 'vue';
import '../css/styles.css'

export default defineComponent({
  name: 'NavBar'
})

</script>