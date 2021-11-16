<template>
  
    <Menu />
    <div class="container mt-4">
    <h1 class="mb-3">Home Page</h1>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellendus asperiores fugiat repellat minima cupiditate quia laboriosam aperiam at dignissimos possimus eos odit sequi, fuga dicta facilis cum, nihil ducimus quidem.</p>
    </div>
     <Footer />

</template>

<script>
// @ is an alias to /src
import Menu  from '@/components/Menu.vue'
import Footer  from '@/components/Footer.vue'

export default {
  name: 'Home',
  components: {
    Menu,
    Footer
  }
}
</script>
