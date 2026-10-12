<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nolb2-_oy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:space-tether-sharp" {...props}></Icon>
<style>
:global(.nolb2-_oy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h5.5v5.5h-5.5zm13 13h5.5v5.5h-5.5zm-7.5-7.5C11.75 8.25 8.5 13 12 13s.25 2.75 3.75 2.75");
}

</style>
