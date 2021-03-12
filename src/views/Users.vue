<template>
  <div>
    <h3>Users</h3>
    <router-link to="/user/1">ユーザー１</router-link>
    <router-link to="/user/2">ユーザー２</router-link>
    <hr>
    <h1>User No. {{ id }}</h1>
    <router-link :to="'/users/' + (Number(id) + 1 ) + '/profile' ">次のユーザー</router-link>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  props: ["id"]
};
</script>