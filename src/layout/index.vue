<template>
  <section id="wrap">
    <h1 class="blind">웹사이트 제목</h1>
    <Header/>
    <section id="container">
      <router-view/>
    </section>
    <Footer/>
  </section>
</template>
<script>
import Header from "@/layout/components/Header";
import Footer from "@/layout/components/Footer";
export default {
  components: {Footer, Header}
}
</script>