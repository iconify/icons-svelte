<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gcf_97b7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:suspenders-sharp" {...props}></Icon>
<style>
:global(.gcf_97b7h) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 2.75V15m7-12.25V15M7 15h3v3.5H7zm7 0h3v3.5h-3zM4 21.25V18.5h16v2.75");
}

</style>
