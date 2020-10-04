<template>

<span>
  <div id="app">
    <header>
     <NavBar cor=" brown lighten-1" logo="Social" url="#"></NavBar> 
     </header>
     <main>
            <div class="container">
              <div class="row">
                <grid-vue tamanho="4">
                    <CardMenuVue>
                      <div class="row valign-wrapper">
                        <grid-vue tamanho="8">
                          <img src="https://materializecss.com/images/yuna.jpg" alt="" class="circle responsive-img"> <!-- notice the "circle" class -->
                        </grid-vue>

                        <grid-vue tamanho="8">
                          <span class="black-text">
                            <h5>Maria Silva</h5>
                          </span>
                        </grid-vue>
                      </div>
                    </CardMenuVue>
                    <CardMenuVue>
                      <h3>Teste</h3>

                    </CardMenuVue>
           </grid-vue>
           <grid-vue tamanho="8">
             <router-view/>  
           </grid-vue>
           
        </div>
       </div>
       
     </main>
    <FooterVue cor=" brown lighten-1" logo="Social" descricao="teste de descricao" ano="2020" >
      <li><a class="grey-text text-lighten-3" href="#!">Home</a></li>
      <li><a class="grey-text text-lighten-3" href="#!">Link 2</a></li>
      <li><a class="grey-text text-lighten-3" href="#!">Link 3</a></li>
      <li><a class="grey-text text-lighten-3" href="#!">Link 4</a></li>
    </FooterVue>

  </div>
  </span>
</template>

<script>
import NavBar from '@/components/layouts/NavBar'
import FooterVue from '@/components/layouts/FooterVue'
import GridVue from '@/components/layouts/GridVue'
import CardMenuVue from '@/components/layouts/CardMenuVue'

export default {
  name: 'App',
  components:{
    NavBar,
    FooterVue,
    GridVue,
    CardMenuVue

  }
}
</script>

<style>

</style>
