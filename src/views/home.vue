<template>
  <section class="container home text-center ">
   <hero/>
   <abilities/>
   <info/>
   <reviews/>
   <newsletter/>
   <app-footer/>
  </section>

  
</template>

<script>
import hero from '../cmps/hero.vue'
import abilities from '../cmps/ability-list.vue'
import info from '../cmps/info.vue'
import reviews from '../cmps/reviews.vue'
import newsletter from '../cmps/newsletter.vue'
import appFooter from '../cmps/app-footer.vue'
export default {
  name: 'home',
  data() {
    return {
    }
  },
  computed: {
  },
  created() {
  },
  methods: {
  },
  components:{
    hero,
    abilities,
    info,
    reviews,
    newsletter,
    appFooter
  }
  
}
</script>
