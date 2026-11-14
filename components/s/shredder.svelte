<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qkszotbnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:shredder" {...props}></Icon>
<style>
:global(.qkszotbnu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 8.5h12a3 3 0 0 1 3 3a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3a3 3 0 0 1 3-3m1.5 0v-5H14v5m-7.5 6V20m4-5.5V21m3.5-6.5v5m3.5-5V21");
}

</style>
