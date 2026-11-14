<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mk2n_vbvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:signal-alert" {...props}></Icon>
<style>
:global(.mk2n_vbvp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 18.5v-3m4.5 3v-6m4.5 6V9m4.5-3.5V14m0 4.5h.01");
}

</style>
