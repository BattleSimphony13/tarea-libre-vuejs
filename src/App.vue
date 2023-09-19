<template>
  <div id="app">
    <h1>{{ playerName }}</h1>
    <img :src="playerImage" alt="Messi's Image" />
  </div>
</template>

<script>
export default {
  data() {
    return {
      playerName: 'Lionel Messi',
      playerImage: 'https://upload.wikimedia.org/wikipedia/commons/b/b4/Lionel-Messi-Argentina-2022-FIFA-World-Cup_%28cropped%29.jpg', // Insert Messi's image URL here
    };
  },
};
</script>
