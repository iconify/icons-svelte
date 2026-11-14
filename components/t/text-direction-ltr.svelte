<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="og0qsk0fs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:text-direction-ltr" {...props}></Icon>
<style>
:global(.og0qsk0fs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.5 3.5v7H10a3.5 3.5 0 0 1 0-7Zm0 0h4m-4 0V14M16 3.5V14M4 19h16m-2.5-2.5L20 19l-2.5 2.5");
}

</style>
