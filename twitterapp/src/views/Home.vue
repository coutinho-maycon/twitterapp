<template>
  <div class="bg-gray-800 ">
    <div class="flex justify-between py-3 px-2 border-b border-gray-600">
      <img class="w-10 h-10 rounded-full" src="https://ef564920920608e03abb-7d34ef097b6ab6c586dfc84157128505.ssl.cf1.rackcdn.com/PostImagem/36734/foto-de-perfil-profissional_o1eh30s23krp31qn41l3havc2fti.JPG" alt="">
      <svg xmlns="http://www.w3.org/2000/svg" class="w-7 h-7" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" role="img" width="1.23em" height="1em" preserveAspectRatio="xMidYMid meet" viewBox="0 0 256 209"><path d="M256 25.45c-9.42 4.177-19.542 7-30.166 8.27c10.845-6.5 19.172-16.793 23.093-29.057a105.183 105.183 0 0 1-33.351 12.745C205.995 7.201 192.346.822 177.239.822c-29.006 0-52.523 23.516-52.523 52.52c0 4.117.465 8.125 1.36 11.97c-43.65-2.191-82.35-23.1-108.255-54.876c-4.52 7.757-7.11 16.78-7.11 26.404c0 18.222 9.273 34.297 23.365 43.716a52.312 52.312 0 0 1-23.79-6.57c-.003.22-.003.44-.003.661c0 25.447 18.104 46.675 42.13 51.5a52.592 52.592 0 0 1-23.718.9c6.683 20.866 26.08 36.05 49.062 36.475c-17.975 14.086-40.622 22.483-65.228 22.483c-4.24 0-8.42-.249-12.529-.734c23.243 14.902 50.85 23.597 80.51 23.597c96.607 0 149.434-80.031 149.434-149.435c0-2.278-.05-4.543-.152-6.795A106.748 106.748 0 0 0 256 25.45" fill="#55acee"/></svg>
      <svg xmlns="http://www.w3.org/2000/svg" class="h-7 w-7 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 3v4M3 5h4M6 17v4m-2-2h4m5-16l2.286 6.857L21 12l-5.714 2.143L13 21l-2.286-6.857L5 12l5.714-2.143L13 3z" /></svg>
    </div>
    <div>
      <PostCard class="m-4"/>
      <PostCard class="m-4"/>
      <PostCard class="m-4"/>
      <PostCard class="m-4"/>
    </div>
    

  </div>
  
</template>

<script>
import PostCard from './PostCard.vue'

export default {
  name: 'App',
  components: {   
    PostCard
  }
}
</script>