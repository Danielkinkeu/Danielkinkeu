<template>
       <section>
    <fieldset>
        <legend><h1>Contact</h1></legend>
        <form>
     <tr>
            <div class="carre">
              <label for="name" class="infos ">Nom :</label>
             <center> <input type="text" id="name" name="user_name" required></center>
          </div>
      </tr>
          <br />
          <div class="carre">
              <label for="name" class="infos ">Prenom :</label>
              <center><input type="text" id="name" name="user_name" required></center>
          </div>
          <br />
          <div class="carre">
              <label for="email" class="infos ">Adresse email:</label>

              <center><input type="email" id="email" required></center>
          </div>
          <br />
          <div class="carre">
              <label for="phone" class="infos ">Numero de telephone :</label>

              <center> <input type="tel" id="phone" name="phone" required></center>
          </div>
          <br />
          <div class="carre">
            <p class="infos "> Commentaire</p>
            <textarea placeholder="une suggestion?       un probleme? " required></textarea>
        </div>
        <br />
        <p id="confirme">
            <span class="carre"> <input type="button" value="Envoyer" ></span>
             <span class="carre"><input type="button" value="Annuler" ></span>
         </p>
         <br />
         </form>
    </fieldset>
</section>
</template>