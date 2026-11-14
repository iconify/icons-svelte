<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d3i_oobsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:smoke-alarm-test" {...props}></Icon>
<style>
:global(.d3i_oobsl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5h19M5 3.5v3a3 3 0 0 0 3 3h8a3 3 0 0 0 3-3v-3m-7 3h.01m-3.51 9L11 18l4.5-4.5");
}

</style>
