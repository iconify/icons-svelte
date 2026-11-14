<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y92yfvboc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:routine-add" {...props}></Icon>
<style>
:global(.y92yfvboc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 3h15.5a1.75 1.75 0 0 1 1.75 1.75a1.75 1.75 0 0 1-1.75 1.75H4.25A1.75 1.75 0 0 1 2.5 4.75A1.75 1.75 0 0 1 4.25 3m0 7h8.5a1.75 1.75 0 0 1 1.75 1.75a1.75 1.75 0 0 1-1.75 1.75h-8.5a1.75 1.75 0 0 1-1.75-1.75A1.75 1.75 0 0 1 4.25 10m0 7h6A1.75 1.75 0 0 1 12 18.75a1.75 1.75 0 0 1-1.75 1.75h-6a1.75 1.75 0 0 1-1.75-1.75A1.75 1.75 0 0 1 4.25 17M18 15v6m-3-3h6");
}

</style>
