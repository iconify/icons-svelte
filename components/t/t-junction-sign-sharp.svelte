<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xdddv4b6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:t-junction-sign-sharp" {...props}></Icon>
<style>
:global(.xdddv4b6g) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 4.75h18.5M2.75 12H8.5v9.25M21.25 12H15.5v9.25M2.75 8.38h2.5m5.5 0h2.5m5.5 0h2.5M12 15.5v3");
}

</style>
