<template>
  <div class="col-3">
    <div class="card shadow">
      <div class="card-body">
        <h5 class="card-title">{{ gerente.nome }}</h5>
        <h6 class="card-subtitle mb-2 text-muted">{{ gerente.agencia }}</h6>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  props: ['gerente']
};

</script>