<template>
  <div class="a">
    <div class="b">
    <div class="c"> <i> <svg aria-hidden="true" data-icon="fingerprint" data-prefix="fas" viewBox="0 0 512 512"><path fill="currentColor" d="M256 246c-13 0-24 11-24 24 1 72-8 142-28 212-2 9 3 30 24 30 10 0 20-7 23-18 13-47 31-125 29-224 0-13-11-24-24-24zm-1-82c-61 0-104 47-103 101 1 48-4 96-13 143a24 24 0 1 0 47 10c10-50 15-102 14-153 0-26 20-53 55-53 31 1 57 26 57 56 1 48-3 96-10 143-3 13 6 26 19 28 20 3 27-15 28-20 8-50 12-101 11-152-1-56-48-102-105-103zm-110-20c-11-8-26-6-34 4-26 31-40 71-39 112 1 38-2 75-9 112-2 13 6 26 19 28 20 3 27-15 28-19 7-40 11-81 10-122 0-30 9-58 28-81 8-10 7-25-3-34zm109-62c-15 0-31 2-46 5a24 24 0 0 0 11 47 140 140 0 0 1 173 131c1 38-1 76-5 113-2 14 8 25 21 27 16 2 25-12 26-21a929 929 0 0 0 6-120c-1-99-85-180-186-182zm252 122c-3-13-15-22-28-19s-22 16-19 29c5 21 5 37 5 62 0 13 10 24 24 24 13 0 24-11 24-24 0-22 0-44-6-72zm-40-91A266 266 0 0 0 253 0C183-1 118 25 70 73 24 119-1 181 0 247v21a24 24 0 1 0 48 2v-24c-1-53 19-102 56-139 39-39 92-60 148-59 70 1 135 36 175 92a24 24 0 1 0 39-27z"></path></svg> </i> <h1 class="d" id="code">机人验证</h1> <h2 class="e">还差一步</h2> </div>
    <div class="c"><Captcha/></div>
    <div class="c"> <p> <span>你说得对，但是「</span><a class="i" href="" target="_blank">原神</a><span>」是由</span> </p> </div>
    <p class="f"> <span>Request ID: 114514</span><span class="g"></span><br class="h"><span>Your IP: 8.8.8.8</span> </p>  
    <p class="j"> Performance &amp; security by <a class="i" href="" target="_blank">Zackiss security center</a> </p>
  </div>
</div>
    
</template>

<script>
import './assets/page.css';
import Captcha from './components/Captcha.vue';
export default {
  name: 'App',
  components: {
    Captcha,
  },
};
</script>
