<template>
  <img
    :src="imgLink"
    alt="Profile Image"
    class="w-8 h-8 object-contain rounded-3xl"
  />
</template>

<script>
export default {
  name: "ProfileImage",
  data() {
    return {
      imgLink:
        "https://e7.pngegg.com/pngimages/428/798/png-clipart-link-the-legend-of-zelda-the-wind-waker-cartoon-the-legend-of-zelda-smiley-fictional-character.png",
    };
  },
};
</script>
