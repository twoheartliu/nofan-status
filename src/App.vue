<script setup lang="ts">
</script>

<template>
  <div class="title">服务器状态</div>
  <div class="quote-fanfou">
    <div class="avatar"><img class="img" src="./assets/img/avatar.jpg" alt="twoheart"></div>
    <div class="content">
      <div class="username"><a href="https://fanfou.com/twoheart" target="_blank">twoheart</a></div>
      <span class="message">
        nofan 已恢复访问。
      </span>
      <div class="meta">
        <a href="https://fanfou.com/statuses/SjdUHgsVSfI">2024 年 04 月 26 日 15:21:03</a> 通过网页
      </div>
    </div>
  </div>
  <div class="quote-fanfou">
    <div class="avatar"><img class="img" src="./assets/img/avatar.jpg" alt="twoheart"></div>
    <div class="content">
      <div class="username"><a href="https://fanfou.com/twoheart" target="_blank">twoheart</a></div>
      <span class="message">
        由于服务器故障，本站暂时无法访问，预计几小时后恢复。
      </span>
      <div class="meta">
        <a href="https://fanfou.com/statuses/SjdUHgsVSfI">2024 年 04 月 26 日 11:18:26</a> 通过网页
      </div>
    </div>
  </div>
</template>

<style scoped>
.title {
  font-size: larger;
  font-weight: bold;
  margin-bottom: 16px;
  color: #333;
  line-height: 1.5;
}

.quote-fanfou {
  font-family: HelveticaNeue, Helvetica Neue, Helvetica, Arial, sans-serif;
  font-style: normal;
  display: flex;
  margin: 16px 0;
  padding: 16px;
  border-radius: 4px;
  background-color: #f8f8f8;
}

.quote-fanfou .username {
  font-size: 14px;
  font-weight: bold;
  color: #333;
  line-height: 1.5;
}

.quote-fanfou .username a {
  text-decoration: none;
  color: #333;
}

.quote-fanfou .avatar {
  margin-right: 12px;
}

.quote-fanfou .avatar .img {
  height: 48px;
  width: 48px;
}

.quote-fanfou .content {
  max-width: 360px;
  font-size: 14px;
  line-height: 20px;
  text-align: left;
}

.quote-fanfou .message {
  word-break: break-all;
}

.quote-fanfou .meta {
  margin-top: 4px;
}

.quote-fanfou .meta,
.quote-fanfou .meta a {
  color: #999;
  font-size: 12px;
}

.quote-fanfou .attachment {
  margin-left: 8px;
}

.quote-fanfou .attachment .img {
  height: 106px;
  width: 106px;
  padding: 2px;
  margin-top: 4px;
  border: 1px solid #eee;
}

@media only screen and (max-width:767px) {
  .quote-fanfou .content {
    max-width: 240px;
  }
}
</style>
