<template>
  <div class="Home">
    <ContentHeader />
    <h1 class="h2">Bienvenue !</h1>
    <CreatePostBtn />
    <ShowAllContents />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import ContentHeader from '@/components/ContentHeader.vue'
import CreatePostBtn from '@/components/CreatePostBtn.vue'
import ShowAllContents from '@/components/ShowAllContents.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'Home',
  components: {
    ContentHeader,
    CreatePostBtn,
    ShowAllContents,
    Footer
  }
}
</script>

<style scoped lang="scss">
</style>