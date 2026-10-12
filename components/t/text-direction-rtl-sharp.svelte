<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6y_9cbje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:text-direction-rtl-sharp" {...props}></Icon>
<style>
:global(.d6y_9cbje) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 3.75v10m4.5-10v10m2-10H9.25a3.5 3.5 0 0 0 0 7h1.25m9.75 7.75H3.75m2.75-2.75L3.75 18.5l2.75 2.75");
}

</style>
