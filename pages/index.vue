<template>
  <div>
    <v-parallax :src="parallaxURL" height="200" class="text-center">
      いつかは沖縄で暮らしたい<br />
      ハードウェアからウェブ、AIまで<br />
      なんでもありのフルスタックエンジニア
    </v-parallax>
    <v-container>
      <v-row>
        <v-col cols="6" md="3">
          <v-img :src="avatarURL" class="rounded-circle"></v-img>
        </v-col>
        <v-col>
          <h1 class="display-1">白柳 大樹</h1>
          <div>自己紹介文はここに</div>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>
export default {
  data() {
    return {
      parallaxURL: require('@/assets/parallax.jpg'),
      avatarURL: require('@/assets/avatar.jpg'),
    }
  },
}
</script>
