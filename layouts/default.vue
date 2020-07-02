<template>
  <v-app>
    <div id="container">
      <!-- 상단 헤더 시작 -->
      <header id="header">
        <div class="header-wrap">
          <h1><a href="#profile">From. J</a></h1>
          <div class="nav-bg" />
          <div class="nav-btn" title="메뉴버튼">
            <span />
            <span />
            <span />
          </div>
          <nav id="nav">
            <h2 class="hidden">
              Menu
            </h2>
            <ul class="navigation">
              <li><a href="javascript:" class="menu0">Profile</a></li>
              <li><a href="javascript:" class="menu1">Skills</a></li>
              <li><a href="javascript:" class="menu2">Career</a></li>
              <li><a href="javascript:" class="menu3">Portfolio</a></li>
            </ul>
          </nav>
        </div>
      </header>
      <!-- 상단 헤더 끝 -->

      <section id="container">
        <nuxt />
      </section>

      <!-- 풋터 시작 -->
      <footer id="footer">
        <h2 class="hidden">
          Contact me
        </h2>
        <dl class="contact-list">
          <dt class="hidden">
            Contact me
          </dt>
          <dd>
            <a href="mailto:4004103@naver.com"><img
              src="img/mail_w.png"
              alt="조수아 이메일"
              title="조수아 이메일"
            ></a>
          </dd>
          <dd>
            <a class="tel-btn" href="tel:01040041006"><img
              src="img/call_w.png"
              alt="조수아 휴대폰 번호"
              title="조수아 휴대폰 번호"
            ></a>
          </dd>
        </dl>
        <a id="return-to-top" href="javascript:void(0);" style="display: inline;"><span><img src="/img/to-top.png" alt="상단으로"></span></a>
      </footer>
      <!-- 풋터 끝 -->
    </div>
  </v-app>
</template>
<script lang="ts">
import { Component, Vue, } from 'vue-property-decorator';

@Component({})
export default class Home extends Vue {
}
</script>
