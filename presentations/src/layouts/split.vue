<template>
  <header>{{ $slidev.configs.title }}</header>
  <div class="slidev-layout split">
    <slot name="default" />
    <div class="left">
      <slot name="left" />
    </div>
    <div class="right">
      <slot name="right" />
    </div>
  </div>
</template>
