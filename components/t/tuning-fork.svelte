<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vf79f0-ii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:tuning-fork" {...props}></Icon>
<style>
:global(.vf79f0-ii) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 2.75v7.5a3.5 3.5 0 0 0 7 0v-7.5m-3.5 11v7.5M4.5 4.5c-1 1.6-1 4.4 0 6m15-6c1 1.6 1 4.4 0 6");
}

</style>
