<template>
  <div id="form-voluntary" class="container">
    <form action="">
      <h3 class="text-center pb-4"><strong>Cadastro Voluntário</strong></h3>
      <span>*Informe o seguintes campos</span>
      <div class="row mt-2 mb-4">
        <div class="col">
          <label class="form-label">Nome</label>
          <input type="text" class="form-control">
        </div>
        <div class="col">
          <label class="form-label">Telefone</label>
          <input type="text" class="form-control">
        </div>
        <div class="col">
          <label class="form-label">Email</label>
          <input type="text" class="form-control">
        </div>
      </div>
      <div class="row mb-4">
        <div class="col">
          <label class="form-label">Celular</label>
          <input type="text" class="form-control">
        </div>
        <div class="col">
          <label class="form-label">CPF</label>
          <input type="text" class="form-control">
        </div>
        <div class="col">
          <label class="form-label">Pais</label>
          <input type="text" class="form-control">
        </div>
      </div>
      <div class="row mb-4">
        <div class="col">
          <label class="form-label">Cidade</label>
          <input type="text" class="form-control">
        </div>
        <div class="col">
          <label class="form-label">Bairro</label>
          <input type="text" class="form-control">
        </div>
        <div class="col">
          <label class="form-label">Logradouro</label>
          <input type="text" class="form-control">
        </div>
      </div>
      <div class="row mb-4">
        <div class="col">
          <label class="form-label">UF</label>
          <input type="text" class="form-control">
        </div>
        <div class="col">
          <label class="form-label">Número</label>
          <input type="text" class="form-control">
        </div>
        <div class="col">
          <label class="form-label">CEP</label>
          <input type="text" class="form-control">
        </div>
      </div>
      <button class="botao">Cadastrar</button>
    </form>
  </div>
</template>

<script>
export default {
  name: "form-voluntary",
  props: ["id"],
  data(){
    return{
      voluntary: {}
    }
  }
}
</script>

<style scoped>
  form{
    margin: 0 auto;
  }

  .botao{
    width: 150px;
    border-radius: 10px;
    color: #fff;
    font-weight: bold;
    background-color: #504B43;
    text-decoration: none;
    font-weight: bold;
    padding: 5px;
  }
</style>