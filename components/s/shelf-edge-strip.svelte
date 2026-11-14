<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xw_9wcb5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:shelf-edge-strip" {...props}></Icon>
<style>
:global(.xw_9wcb5j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8h19v8h-19Zm2.25 2.75H10m-5.25 2.5H8M12 8v8m2-5.25h5.25M14 13.25h3.25");
}

</style>
