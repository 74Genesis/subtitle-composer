
<script lang="ts" setup>
import { Player, Video } from "@vime/vue-next";
import { onMounted } from "#imports";
import "@vime/core/themes/default.css";
import "@vime/core/themes/light.css";

onMounted(() => {});
</script>
<template>
  <div>
    <video controls>
      <source src="https://yewtu.be/latest_version?id=RKK7wGAYP6k" />
    </video>
    <Player controls>
      <Video controls>
        <source src="/testvid.mp4" />
        <!-- <source
          data-src="https://yewtu.be/embed/RKK7wGAYP6k"
          type="video/mp4"
        /> -->
        <!-- <track
          default
          kind="subtitles"
          src="https://media.vimejs.com/subs/english.vtt"
          srclang="en"
          label="English"
        /> -->
      </Video>
    </Player>

    <!-- <Youtube video-id="RKK7wGAYP6k" /> -->
  </div>
</template>
<style lang="scss">
body {
  background-color: rgb(128, 0, 255);
}
span.ytp-caption-segment {
  background-color: red !important;
}
</style>
