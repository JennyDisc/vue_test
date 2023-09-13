<template>
  <div class="container">
    <div class="row">
      <div class="col"></div>
      <div class="col-6">
        <img
          src="https://images.unsplash.com/photo-1537047902294-62a40c20a6ae?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1935&q=80"
          class="img-fluid"
          alt="登入畫面背景圖"
        />
      </div>
      <div class="col-4 my-auto">
        <form id="form">
          <h1 class="mb-4">華特義式餐廳</h1>
          <input
            type="text"
            placeholder="請輸入帳號"
            class="mb-3 px-3 pe-4 py-2"
          />
          <input
            type="text"
            placeholder="請輸入電子郵件"
            class="mb-3 px-3 pe-4 py-2"
          />
          <input
            type="text"
            placeholder="請輸入密碼"
            class="mb-4 px-3 pe-4 py-2"
          />
          <button class="btn btn-lg btn-primary w-75" type="submit">
            登入
          </button>
        </form>
      </div>
      <div class="col"></div>
    </div>
  </div>
  <router-view></router-view>
</template>

<script>
import { RouterView } from "vue-router";

export default {
  components: {
    RouterView,
  },
};
</script>
