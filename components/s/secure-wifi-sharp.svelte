<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m1t_8ebac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:secure-wifi-sharp" {...props}></Icon>
<style>
:global(.m1t_8ebac) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 9a13 13 0 0 1 18.5 0M6 12.25a8.5 8.5 0 0 1 12 0m-9 3h6v6H9zm1.5 0V12.5h3v2.75");
}

</style>
