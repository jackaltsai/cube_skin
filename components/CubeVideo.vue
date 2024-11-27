<template>
    <div>
      <video class="h-full w-full rounded-lg" controls autoPlay>
      <source src="/img/CubeVideo.mp4" type="video/mp4" />
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
        autoplay: true,
        loop: false,
        muted: false,
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
  