<template>
<div>
     <router-link :to="{name :'home' }">Home</router-link>
     <router-link :to="{name :'login' }">login</router-link>
     <router-link :to="{name :'register' }">register</router-link>
</div>
<router-view></router-view>
</template>
