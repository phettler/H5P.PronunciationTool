<template>
      <div class="text">{{ word.answer }}</div>
      <div class="audio">
      <audio v-bind:controls="word.audio.controls" v-bind:autoplay="word.audio.autoplay" v-for="file in word.audio.files">
        <source v-bind:src="file.path" v-bind:type="file.mime">
      </audio>
      </div>
</template>

<style lang="scss" type="text/scss">
  .audio-recorder-wordlist .word{
    display:flex;
  }
  .audio-recorder-wordlist .word > div{
    display:flex;
    justify-content: center;
    padding: 3px;
    align-items: center;
    width:50%;
  }
  .audio-recorder-wordlist .word .text{
    font-weight:700;
  }
</style>
