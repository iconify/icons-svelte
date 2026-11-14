<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mj5ag2bke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:traffic-flood" {...props}></Icon>
<style>
:global(.mj5ag2bke) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8c2-2.5 4 2.5 6.5 0s4.5 2.5 7 0s4 0 5.5 0m-19 5c2-2.5 4 2.5 6.5 0s4.5 2.5 7 0s4 0 5.5 0m-19 5c2-2.5 4 2.5 6.5 0s4.5 2.5 7 0s4 0 5.5 0");
}

</style>
