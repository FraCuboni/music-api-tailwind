<script>
import SearchBar from './components/SearchBar.vue';
import SearchPage from './components/SearchPage.vue'
export default{
  name: 'App',
  components:{
    SearchBar,
    SearchPage,
  },
  data(){
    return{

    }
  },
  methods:{

  },
  mounted(){

  },
}
</script>

<template>
  <div class="container">
    <SearchBar />
    <router-view></router-view>
  </div>
  
</template>

<style scoped lang="scss">
@use '../styles/partials/variables.scss' as *;

.container{
  background-color: $black;

}
</style>
