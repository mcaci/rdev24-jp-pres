<template>
  <div class="slidev-layout jp-end">
    <slot>END</slot>
  </div>
</template>

<style scoped lang="postcss">
.slidev-layout.jp-end {
  @apply text-red text-opacity-85 text-center place-content-center font-size-5;
  background-image: url('/images/kanji8.jpeg');
  background-size: cover;
  background-repeat: no-repeat;
  background-position-y: 20%;
}
</style>