<template>
  <div class="about">
    <Navbar/>
    <div>
      <h1 class="kr-des">목적</h1>
      <h2>
        - 다수의 음성/사운드 녹음 채널에서 특정 조건을 빠르게 검색 <br>
        - 녹음된 소리의 상태를 시간대별로 분류하는 기능 <br>
        - 채널별 시간축에 소리의 상태를 나타내주어 빠르게 해당 위치로 찾아갈 수 있도록 할것 <br>
      </h2>
    </div>
    <div>
      <h1 class="en-des">Target</h1>
      <h2>
        - Quick search for specific conditions in multiple voice/sound recording channels <br>
        - Ability to classify the recorded sound state by time period <br>
        - Display the state of sound on the time axis for each channel so that you can quickly find the location <br/>

      </h2>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue'

export default {
  name: 'HomeView',
  components: {
    Navbar
  }
}
</script>
<style>

</style>
