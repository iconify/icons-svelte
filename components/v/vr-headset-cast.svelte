<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nrb_czbbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:vr-headset-cast" {...props}></Icon>
<style>
:global(.nrb_czbbt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 13h8a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2h-2a2 2 0 0 0-4 0h-2a2 2 0 0 1-2-2v-4a2 2 0 0 1 2-2M15.125 2.5h3.75A2.625 2.625 0 0 1 21.5 5.125v1.75A2.625 2.625 0 0 1 18.875 9.5h-3.75A2.625 2.625 0 0 1 12.5 6.875v-1.75A2.625 2.625 0 0 1 15.125 2.5M5.5 10l4-4m-3 0h3v3");
}

</style>
