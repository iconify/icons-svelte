<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gf5dhjepw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:snow-depth" {...props}></Icon>
<style>
:global(.gf5dhjepw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 16V3.5a1 1 0 0 1 1-1h3a1 1 0 0 1 1 1V16m-12 5c1.5-3.5 4.5-5 7-5h5c2.5 0 5.5 1.5 7 5Zm7-15h2m-2 3.5h2m-2 3.5h2");
}

</style>
