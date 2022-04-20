<template>
  <div class="container">
    <h1>Vue.js + Github</h1>
    <p class="lead">
      Listar issues de um repositório Github, usando Vue.js
    </p>

    <div class="row">
      <div class="col">
        <div class="form-group">
          <input type="text" class="form-control" placeholder="Github username">
        </div>
      </div>

      <div class="col">
        <div class="form-group">
          <input type="text" class="form-control" placeholder="Github repositório">
        </div>
      </div>

      <div class="col-3">
        <div class="form-group">
          <button class="btn btn-success">Pesquisar</button>
          <button class="btn btn-danger">Limpar</button>
        </div>
      </div>
    </div>
    <br>


    <table class="table table-sm table-bordered">
      <thead>
        <tr>
          <th width="100">Número</th>
          <th>Título</th>
        </tr>
      </thead>

      <tbody>
        <tr>
          <td class="text-center" colspan="2">Nenhuma issue encontrada!</td>
        </tr>
      </tbody>
    </table>
  </div>
</template>

<script>
export default {
  name: 'GitHubIssues',

  data() {
    return {
    };
  },

  methods: {},
};
</script>

<style>

</style>
