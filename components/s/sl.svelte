<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o7rw0ot1i"/><path class="cdun8qyge"/><path class="v9r4c5bup"/><path class="g4iy7n_ne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:sl" {...props}></Icon>
<style>
:global(.cdun8qyge) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.79 20.29a15.79 15.79 0 0 1-31.58 0");
}

:global(.g4iy7n_ne) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.41 23.26a2.22 2.22 0 0 0 1.85.83h1.12a1.86 1.86 0 0 0 1.86-1.85a1.86 1.86 0 0 0-1.86-1.86h-1.21a1.87 1.87 0 0 1-1.86-1.86a1.87 1.87 0 0 1 1.86-1.86h1.12a2 2 0 0 1 1.85.84m4.65-.93V24h3.71");
}

:global(.o7rw0ot1i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 20.29a19.5 19.5 0 0 1-39 0");
}

:global(.v9r4c5bup) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.07 20.29a12.07 12.07 0 0 1-24.14 0m24.14 0a12.07 12.07 0 1 0-24.14 0");
}

</style>
