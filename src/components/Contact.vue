<template>
  <div id="contact">
    <div class="title">
      <h2>Contactez-nous !</h2>
      <span class="underline"></span>
    </div>
    <div id="main-contact">
      <form>
        <div class="form-row">
          <label for="exampleInputEmail1" class="form-label">Email <span>*</span></label>
          <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="name@example.com">
        </div>
        <div class="form-row">
          <label for="exampleInputText" class="form-label">Objet <span>*</span></label>
          <input type="text" class="form-control" id="exampleInputText" aria-describedby="emailHelp" placeholder="Objet de la demande">
        </div>
        <div class="form-row">
          <label for="exampleFormControlTextarea1" class="form-label">Message <span>*</span></label>
          <textarea class="form-control" id="exampleFormControlTextarea1" placeholder="Votre Message"></textarea>
        </div>
        <div class="form-row form-check">
          <input type="checkbox" class="form-check-input" id="exampleCheck1">
          <label class="form-check-label" for="exampleCheck1">J'ai lu et j'accepte la <a href="#">Politique de confidentialité</a><span>*</span></label>
        </div>
        <button type="submit" class="btn">Envoyer</button>
      </form>
    </div>
  </div>
</template>

<script>
export default {
name: "Contact"
}
</script>

<style scoped>

</style>