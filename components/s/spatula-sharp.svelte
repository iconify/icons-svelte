<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n6t0_1bzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:spatula-sharp" {...props}></Icon>
<style>
:global(.n6t0_1bzc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 2.75h9v8.5h-9zm3 2.75v3m3-3v3M12 11.25v4.25m-1.5 0h3v5.75h-3z");
}

</style>
