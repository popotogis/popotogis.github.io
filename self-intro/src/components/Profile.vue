<template>
    <div class = "profile">
        <h1>popotogis (T.Nakano)</h1>
        <div class = "intro">
            <p>
            2000年生まれ。
            映画"館"が好き。
            </p>
        </div>
        <div class = "EducationlaBG">
        2016/4 明治大学付属中野八王子高等学校入学<br>
        2019/3 明治大学付属中野八王子高等学校卒業<br>
        2019/4 明治大学 総合数理学部 先端メディアサイエンス学科 入学<br>
        </div>
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'HelloWorld',
  props: {
    msg: String,
  },
});
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1{
   font-size: 20pt; 
}
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
