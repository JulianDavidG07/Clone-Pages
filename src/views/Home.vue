<template>
  <div class="block md:container md:mx-auto">
    <Search />
    <Navbar />
    <Content />
    <Card />
    <CardBlack />
    <CardWhite />
    <CardGray />
    <Footer />
    <!-- <Form /> -->
  </div>
</template>

<script>
// @ is an alias to /src
import Search from '@/components/Search.vue'
import Navbar from "@/components/Navbar.vue";
import Content from '@/components/Content.vue'
// import Form from '@/components/Form.vue'
import Card from '@/components/Card.vue'
import CardBlack from "@/components/CardBlack.vue";
import CardWhite from "@/components/CardWhite.vue";
import CardGray from "@/components/CardGray.vue";
import Footer from "@/components/Footer.vue"

export default {
  name: 'Home',
  components: {
    Search,
    Navbar,
    Content,
    // Form,
    Card,
    CardBlack,
    CardWhite,
    CardGray,
    Footer

  }
}
</script>
