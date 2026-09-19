<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jic6870rr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:soundid" {...props}></Icon>
<style>
:global(.jic6870rr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.71 20.216h26.579v7.568H10.71zm5.432 17.933l10.364-10.364l5.351 5.351L21.493 43.5zm0-23.284L26.506 4.5l5.351 5.351l-10.364 10.364z");
}

</style>
