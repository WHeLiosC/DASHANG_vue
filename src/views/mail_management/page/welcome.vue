<template>
  <div id="welcome">
    <h3>欢迎您，{{username}}</h3>
    <div>共有 {{num}} 封 <a href="" value="未读邮件">未读邮件</a></div>
  </div>
</template>
<script>
export default {
  name: "welcome",
  data() {
    return {
      username: "冯卓",
      num: '66'
    };
  }
};
</script>