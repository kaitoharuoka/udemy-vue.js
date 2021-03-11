<template>
  <div>
    <h3>Users</h3>
    <router-link to="/user/1">ユーザー１</router-link>
    <router-link to="/user/2">ユーザー２</router-link>
    <hr>
    <h1>User No. {{ $route.params.id }}</h1>
  </div>
</template>

