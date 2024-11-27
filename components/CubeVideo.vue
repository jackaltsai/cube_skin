<template>
    <div>
      <video 
        ref="videoPlayer" 
        :src="videoSrc" 
        :controls="controls" 
        :autoplay="autoplay" 
        :loop="loop" 
        @play="onPlay" 
        @pause="onPause" 
        style="max-width: 100%;"
      >
        Your browser does not support the video tag.
      </video>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        videoSrc: "/img/CubeVideo.mp4", // Replace with your video URL
        controls: true,
        autoplay: false,
        loop: false,
        muted: false,
        type: "video/mp4",
      };
    },
    methods: {
      playVideo() {
        this.$refs.videoPlayer.play();
      },
      pauseVideo() {
        this.$refs.videoPlayer.pause();
      },
      toggleMute() {
        this.$refs.videoPlayer.muted = !this.$refs.videoPlayer.muted;
      },
      onPlay() {
        console.log("Video is playing!");
      },
      onPause() {
        console.log("Video is paused.");
      },
    },
  };
  </script>
  
  <style>
  
  </style>
  