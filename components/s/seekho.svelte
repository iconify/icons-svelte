<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h-0o86bxs"/><path class="xotlkxbcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:seekho" {...props}></Icon>
<style>
:global(.h-0o86bxs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.091 3.5c4.478 4.815.337 9.722.337 9.722l-8.035 7.882l5.643 5.704l-5.06 4.999L9.334 21.165z");
}

:global(.xotlkxbcz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.909 44.5c-4.478-4.815-.337-9.722-.337-9.722l8.035-7.882l-5.643-5.704l5.06-4.999l10.642 10.642z");
}

</style>
