<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ei_ekbium"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:smart-guides" {...props}></Icon>
<style>
:global(.ei_ekbium) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7h7m2.75 0H15m2.75 0h3.75M7 2.5v7m0 2.75V15m0 2.75v3.75M10 10h11.5v11.5H10Z");
}

</style>
