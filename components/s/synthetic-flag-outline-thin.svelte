<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="medja4cva"/><path class="ndddypvah"/><path class="qot4e3zhe"/><path class="qhkmcqbdq"/><path class="xhkxitbia"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:synthetic-flag-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.medja4cva) {
  d: path("M5 4v12");
}

:global(.ndddypvah) {
  d: path("M5 5h3v3H5");
}

:global(.qhkmcqbdq) {
  d: path("M13 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.qot4e3zhe) {
  d: path("M8 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.xhkxitbia) {
  d: path("M18 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
