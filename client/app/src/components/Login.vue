<template>
  <div class="posts">
    <h1>Login</h1>
      <div class="form">
        <div>
          <input type="email" name="useremail" placeholder="email" v-model="email">
        </div>
        <div>
          <input type="password" name="password" placeholder="password" v-model="password">
        </div>
        <div>
          <button class="app_login_btn" @click="authenticate">Login</button>
        </div>
      </div>
  </div>
</template>

<script>
// import PostsService from '@/services/PostsService'
// export default {
//   name: 'Login',
//   data () {
//     return {
//       title: '',
//       description: ''
//     }
//   },
//   methods: {
//     async addPost () {
//       await PostsService.addPost({
//         title: this.title,
//         description: this.description
//       })
//       this.$router.push({ name: 'Posts' })
//     }
//   }
// }
</script>
<style type="text/css">
.form input {
  width: 500px;
  padding: 10px;
  border: 1px solid #e0dede;
  outline: none;
  font-size: 12px;
}
.form div {
  margin: 20px;
}
.app_login_btn {
  background: #4d7ef7;
  color: #fff;
  padding: 10px 80px;
  text-transform: uppercase;
  font-size: 12px;
  font-weight: bold;
  width: 520px;
  border: none;
  cursor: pointer;
}
</style>
