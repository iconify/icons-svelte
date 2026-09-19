<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h90qnhbzc"/><circle class="nte9m5b0t"/><circle class="zll03abgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:social-deal" {...props}></Icon>
<style>
:global(.h90qnhbzc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.818 28.465c0 .694-.596 1.252-1.286 1.182c-6.358-.644-11.32-6.013-11.32-12.541s4.962-11.897 11.32-12.541c.69-.07 1.286.488 1.286 1.182zm2.364-8.93c0-.694.596-1.252 1.286-1.182c6.358.644 11.32 6.013 11.32 12.541s-4.962 11.897-11.32 12.541c-.69.07-1.286-.488-1.286-1.182z");
}

:global(.nte9m5b0t) {
  cx: 16.515px;
  cy: 37.197px;
  r: 6.303px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.zll03abgh) {
  cx: 31.485px;
  cy: 10.803px;
  r: 6.303px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
