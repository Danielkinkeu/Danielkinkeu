<script setup>
import { RouterLink, RouterView } from 'vue-router'

</script>

<template>
    <header id="tete">
        <div id="tet">
           <center> <img id="sklf" src="images/icone.jpg" alt="sklf"/> </center>
        </div>
            <nav>
                <RouterLink to="/">Acceuil</RouterLink>
                <RouterLink to="/about">A propos de moi</RouterLink>
                <RouterLink to="/product">Autre produit</RouterLink>
                <RouterLink to="/contact">contact</RouterLink>
            </nav>
        </header>
          <RouterView />
        <footer>
       
            <div id="deuxiemeTrait"></div>
            <div id="copyrightEtIcons">
                <div id="copyright">
                    <span>© SKLF; 2022</span>
                </div>
            </div>
        </footer>


</template>

<style scoped>

</style>
