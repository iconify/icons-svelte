<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="paut2puby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:safety-light-curtain" {...props}></Icon>
<style>
:global(.paut2puby) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 2.5h3.5v19H3Zm14.5 0H21v19h-3.5ZM9.25 7h5.5m-5.5 5h5.5m-5.5 5h5.5");
}

</style>
