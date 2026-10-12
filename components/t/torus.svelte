<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lgikgacmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:torus" {...props}></Icon>
<style>
:global(.lgikgacmn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12a9.25 6.75 0 1 0 18.5 0a9.25 6.75 0 1 0-18.5 0m4.75-.5a4.5 2.5 0 1 1 9 0a4.5 2.5 0 1 1-9 0");
}

</style>
