<template>
  <div class="about">
    <h1>My name is {{ their_name }}</h1>
    <p>
      I am a Creative Visionary. I come with an unconventional resume and tons
      of unique experience, making me the perfect person to change up stale
      conversations, craft unique solutions to problems, and think big picture.
    </p>
    <p>
      I'm driven, think outside the box, and have big dreams of a new start -
      meaning I'm ready to work as hard as it takes to find a career that’s
      meaningful and lucrative.
    </p>
  </div>
</template>

<script>
export default {
  name: 'About',
  data() {
    return {
      their_name: this.$route.params.name,
    };
  },
};
</script>
