<template>
  <div>
    <input
      class="input py-5px px-2 bg-grey-200 text-grey-800 m-2px"
      type="text"
      :value="inputString"
      @keydown.prevent.stop="handleKeyDown"
    >
  </div>
</template>

<script src="./hotkeyInput.ts" lang="ts"></script>
<style src="./hotkeyInput.sass" lang="sass" scoped></style>
