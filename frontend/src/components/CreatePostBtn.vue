<template>
    <div class="my-3 postBtn">
        <b-button variant="light" @click="goCreatePostPage">+ Créer un post !</b-button>
    </div>
</template>

<script>
import router from "@/router"

export default {
  name: 'CreatePostBtn',
  props: {
  },
  data() {
    return {
      signUpForm: {
        email: '',
        userName: '',
        password: '',
        
      }
    }
  },
  methods: {
    goCreatePostPage() {
        router.push({ path: '/create_post' });
    }
  },
}
</script>


<style scoped lang="scss">
</style>