<template>
  <div class="box">
    <div class="footer">
      <button-explore></button-explore>
      <button-video></button-video>
      <button-myself></button-myself>
      <button-friend></button-friend>
      <button-user></button-user>
    </div>
    <router-view></router-view>
  </div>
  
</template>

<script>
  import buttonExplore from './components/explore/buttonExplore'
  import buttonVideo from './components/video/buttonVideo'
  import buttonMyself from './components/myself/buttonMyself'
  import buttonFriend from './components/friend/buttonFriend'
  import buttonUser from './components/user/buttonUser'
  import './css/appvue.css'
  export default {
    name: 'app',
    components: {
      'button-explore': buttonExplore,
      'button-video': buttonVideo,
      'button-myself': buttonMyself,
      'button-friend': buttonFriend,
      'button-user': buttonUser
    }
  }
</script>

<style>
 
</style>
