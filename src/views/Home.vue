<template>
  <div class="home">
    <h1>MY TODO LIST</h1>
    <ul>
      <li>스터디 공부하기</li>
      <li>냉면 사오기</li>
      <li>업무</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Home',
  components: {
  }
}
</script>

<style scoped lang="scss">
.home{
  background: #ECF0F3;
  padding: 50px;
}
h1 {
  margin: 30px auto;
  width: 300px;
  height: 60px;
  line-height: 60px;
  color: #555;
  background: #E3E6EC;
  box-shadow: 5px 5px 10px #D1D9E6, -5px -5px 10px #FFFFFF;
  border-radius: 10px;
}
ul{
  margin: 0 auto;
  width: 360px;
  height: 450px;
  background: #E3E6EC;
  box-shadow: 5px 5px 10px #D1D9E6, -5px -5px 10px #FFFFFF;
  border-radius: 10px;
  padding: 30px 30px;
  li {
    list-style: none;
    width: calc(100%-10px);
    height: 40px;
    line-height: 40px;
    text-align: left;
    background: #E6E9EF;
    box-shadow: inset 2px 2px 10px #D1D9E6, inset -2px -2px 10px #FFFFFF;
    border-radius: 8px;
    padding: 5px 10px;
    margin-bottom: 20px;
    color: #3F4A62;

  }
}
</style>
