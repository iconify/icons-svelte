<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mucleibcg"/><circle class="bktfm5bpg"/><path class="kzeo7f65v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:secure-signin" {...props}></Icon>
<style>
:global(.bktfm5bpg) {
  cx: 24px;
  cy: 20.206px;
  r: 4.299px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.kzeo7f65v) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.589 32.093a7.589 7.589 0 1 0-15.178 0");
}

:global(.mucleibcg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 43.5c9.043-3.117 15.488-10.363 16.5-19.589c.28-4.005.256-8.025-.072-12.027a2.54 2.54 0 0 0-2.467-2.366c-4.091-.126-8.846-.808-12.52-4.427a2.05 2.05 0 0 0-2.881 0c-3.675 3.619-8.43 4.301-12.52 4.427a2.54 2.54 0 0 0-2.468 2.366A79.4 79.4 0 0 0 7.5 23.911C8.51 33.137 14.957 40.383 24 43.5");
}

</style>
