<template>
  <div id="app">
    <Header/>
    <FirstView/>
    <EchoLowTech/>
    <HighTechvsLowTech/>
    <Partenaires/>
    <Ekip/>
    <Contact/>
    <Footer/>
  </div>
</template>

<script>

import Header from "@/components/Header";
import FirstView from "@/components/FirstView";
import Ekip from "@/components/Ekip";
import EchoLowTech from "@/components/EchoLowTech";
import Footer from "@/components/Footer";
import Contact from "@/components/Contact";
import HighTechvsLowTech from "@/components/HighTechvsLowTech";
import Partenaires from "@/components/Partenaires";
export default {
  name: 'App',
  components: {
    Partenaires,
    HighTechvsLowTech,
    Contact,
    Footer,
    EchoLowTech,
    Ekip,
    FirstView,
    Header
  }
}

</script>

<style>
</style>
