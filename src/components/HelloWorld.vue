<template>
  <div class="hello">
    <h1>Задание от начинающего веб-разработчика</h1>
    <p>
      За несколько часов я попробовал сделать страничку по вашему макету.<br>
      Я использовал Bootstrap, Vue, JS, CSS, HTML.<br>
      <a href="/About">Открыть задание</a>.
    </p>
    <h3>Installed CLI Plugins</h3>
    <ul>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel" target="_blank" rel="noopener">babel</a></li>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-router" target="_blank" rel="noopener">router</a></li>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-vuex" target="_blank" rel="noopener">vuex</a></li>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint" target="_blank" rel="noopener">eslint</a></li>
    </ul>
    <h3>Об Авторе</h3>
    <ul>
      <li><a href="https://hh.ru/resume/a47ecc63ff0784cb710039ed1f434c484c7948" target="_blank" rel="noopener">Резюме</a></li>
      <li><a href="https://ru.linkedin.com/in/andrew-podprugin-a730a056" rel="noopener">LinkedIN</a></li>
      <li><a href="mailto:anpodin@gmail.com" target="_blank" rel="noopener">Почта</a></li>
      <li><a href="tel:+79261672915" target="_blank" rel="noopener">Телефон</a></li>
    </ul>
    <p>© Все права защищены 2020 Андрей Подпругин</p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
