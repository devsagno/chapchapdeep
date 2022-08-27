<template>
  <div class="app">
  <div class="row">
      <div class="col-md-4">
         <div class="card">
           <div class="card-body">
           <h6 class="card-title">si l'app ne souvre pas dans quelques second ?</h6>
           <h6 class="card-title"> cela veut qu'il nest pas installe dans votre telephone</h6>
            <h6 class="card-title">Veillez intaller l'app et clicker encore sur lien</h6>
           <div>
             <button class="btn btn-primary" href=""> je telecharge pour Android</button>
           </div>
          <div>
         <a class="btn btn-primary" href=""> je telecharge pour Iphone</a>
          </div>
            
           </div>
         </div>
      </div>
    </div>
</div>
</template>

<script>
export default {
    head(){
        return{
            title:"Deep site de Chap Chap",
            meta: [
           {
          name: 'Chap Chap deep site',
          content: 'Chap chap.'
        },
        {
          property: 'og:description',
          content: 'Une de reduction de prix a ete fait sur ce produit'
        },
        {
          property: 'og:title',
          content: 'Achete sur Chap Chap en cliquant sur la photo'
        },
        {
          property: 'og:url',
          content:this.$nuxt.$route.path
        },
        {
          property: 'og:type',
          content: 'article',
        },
        {
          property: 'og:image',
          content:this.$nuxt.$route.path.split('/').pop(),
        },
        ]
        }
    },

}
</script>

<style>
.app{
  margin-top: 10px;
  text-align: center;
}
</style>