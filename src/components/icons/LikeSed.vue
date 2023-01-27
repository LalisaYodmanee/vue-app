<script setup>
import { ref } from "vue";
const like = ref(0);
function likeClick() {
  like.value++;
}
function likeClick2() {
  like.value--;
}
</script>

<template>
  <div>
    <button class="button" @click="likeClick()">
      <img
        src="https://lh3.googleusercontent.com/BItEhVmnGIVmur9hVpgDq3UUOGcVM0yBf2wYBGDcKGIqOY0k8OtgcPVtX02Ou59HNIiGkbiRwQsYUoupiNsNMMu6xDsOmp7F9oHu7VYXuUjEn-n--PMhZhPSajQh5Q7XoiOMri1I8lT90N9kNsdsP5VcIcjkJRM7TLTI-o5WyXyPhlU1MYlvCkj4d4AkxiRfeMKu0lDOH5e9pxJM4qyFOTRbS53YTB5W_iJ2p6eU5i1FLiUJFo7F_tOwAcgYIg6-V4BnVSdwL-_WWAadBi5XFBhAVf1hvkCNNruEjG-bIYaN7dL1xiW2aW0xPHlbcpaGefCDVcFOc2sdc20WB5UspTzf4RZXVKMCUF4hyHX2LUuey6u_84xGtKbuyZe5o8ss56EvwhxSrM1IZnI_fGzsK_jXRPwAd4I2PhZlZz4PDalhM0EnWPZRDPgclfzsJLbfyeyvvwABTOYl2svCggUVy8ICyJGqMGDx-ub-zH9wU1_iA36XYETb8pTJ1L2OgzlKi6CF1Lww8iCIVdWjyjDOgdnvPwm7b-T1vznRfnBxq6Kzs8-koizGHWErvylUcsr8tJqIp86YTsKePFQDiLVIT0VmmHFFHuPDYD8JpqltVf8cTFEGXSeBOQ14ZruP2HuUqfFQ8sCQuDsvfMYnIqz9c3W9QnO6Lr5J-S2QIPRV_yUp4ta2xhedFUx51ywNpdweuQRJlHqVA8D0KjOJ6E3bSp1_ZFV7wRLdiGWtcKzls3T5X_J0X829s2zu18lPuZ4WAwW3FzWezAU9fKOifWYq-38K164p3NLOlf4uZTpK5kGVDYmS0KHgnO1XgJ3hl7qiK9pfOvy1w3ZQQ6HL_E8Im7Pz7YwyONl5plrzR_jawu31qS9mCiMc5hHLxnDRpPB3vOpUR38dnPH7168A_n6h02Rm3ESSstBZ7Y5mV5oYvcwuBSDWma4t5z2GKANVA9mqDay2jjPCFczyThBGkMxO=w894-h893-no?authuser=0"
        width="40"
        height="40"
        aly="like"
      />
    </button>
    <big style="margin: 10px">{{ like }}</big>
    <button class="button2" @click="likeClick2()">
      <img
        src="https://lh3.googleusercontent.com/ZKYH9dT5OgHU4fb8IsehqR0iOtZNxhn516a80vbcVniaAvmNaEr4FyJEVRYziu_SbzccpPR3CZsfsDS9Q4OhnAMNNOYe2SXutaAmnQbY-dUbZzGnACpsF6_R7nPUIdNAyQ8U1WW1tsa_l3MxL7qr8oyHFcQH3NcKj7mVgbM8g_i0-gASrAUriOlR0Z9O0u8s3Nq-56aUZZegA4EI_AMJNsoihK3mlBCgkS6HvIJaTL954A7vxV3Sl6krnnRS8e6GZdq_FUDPr3-dgD8JJ-lY9CGmNVaWJVm0ycKoE3ggJpXYZXdey5ZtZdnBFyiM-pvGTOG3jW2ac9HXQia3sF4g9p8SorGXZ3Tv0kohtUapFX98MZXf26hteVQfaCWOgnV5PjxldCPu-SHgb5GTQZCXsTWNxUtkTYg7bd7EPTcZwIRMnXO6nMXrtkl8LlcElgSdX0_xmtLherwCtWqRTbmj0sT758oO4Y9jTU70Db_kj8SlsT6WEvuejB8rTRafhGEjDPYz8MymrbesYtoi8rvaAUij3vGszfHrBSO0GlLrd7O2GvOXVkimrxw8xkawVx9_oFSMuuS_h6wVu8ae6kFArYRZnbfPu7zqbI53cmnybNNvQUyuMvHSlwdOO_xp6JhUEdklw_N7Z9CYf0j6V9VQJBlrCJlqW2Hd8R9hiIww3UMpVORe8iCSPcXkBH7LNKycjmuEdHjBjiT2WLxD2-EeF8t0ffU2aF2EhfFPC-voKJ6baq0H9GZD01q_FPYXDNoDz1-fGmWnMjL890ItEEiPEPSe8Bu4_SsaYPiM-hJjwILowA0EKOGGonAfGS9YxbMaPe5iM46bWXg82Ux3TNw6nQf5HSh2hL5uOoU9r0URiQ_5I0Xw8Nx2Tj-Xx7jOabxuzYNJq5545cVMN-Gtz2A4y-whvxmF44UeCGRumiXujCpGgkq4Jo4IZlIx4Hh6brphcr0jtmg2uO4gHYQ8aukS=s893-no?authuser=0"
        width="40"
        height="40"
        aly="sad"
      />
    </button>
  </div>
</template>

<style scoped>
.button {
  background-color: lime;
  transition-duration: 0.3s;
}
.button:hover {
  box-shadow: 0 0 3px 2px darkgray;
  background-color: rgb(0, 224, 0);
}
.button:active {
  box-shadow: 0 0 4px 2px gray;
}
.button2 {
  background-color: rgb(255, 128, 128);
  transition-duration: 0.3s;
}
.button2:hover {
  box-shadow: 0 0 3px 2px darkgray;
  background-color: rgb(255, 64, 64);
}
.button2:active {
  box-shadow: 0 0 4px 2px gray;
}
</style>

