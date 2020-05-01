<template>
  <div class="row" id="appSmall">
    <div class="col-sm">
      <input v-model="search" type="text" class="form-control" placeholder=
        "Поиск по системе" aria-label=
               "Recipient's username" aria-describedby="button-addon2">
    </div>
    <div class="col-sm"><p>{{ search }}</p></div>
    <div class="col-sm">
      <div>
        <img class="rounded" src="/img/Layer_40.png" alt="avatar">
        <div><b> Александра В.</b><br>
          superuser</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Survey',
  props: {
    search: String,
  },
};
</script>

<style scoped>

</style>
