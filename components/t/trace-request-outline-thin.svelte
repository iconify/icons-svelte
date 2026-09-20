<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gvmyg7bww"/><path class="puqp14a3r"/><path class="gwbi1m5_l"/><path class="u5k3kbbab"/><path class="bie4u9bix"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:trace-request-outline-thin" {...props}></Icon>
<style>
:global(.bie4u9bix) {
  d: path("M19 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.gvmyg7bww) {
  d: path("M2 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.gwbi1m5_l) {
  d: path("M12 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.puqp14a3r) {
  d: path("m6 7 6 6");
}

:global(.u5k3kbbab) {
  d: path("M16 15h4");
}

</style>
