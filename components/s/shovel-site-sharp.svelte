<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-arwj2fm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:shovel-site-sharp" {...props}></Icon>
<style>
:global(.a-arwj2fm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.5 13.25h8v8h-8v-3.5Zm4 0v-7m-2.25 0h4.5m-4.5 0v-3.5h4.5v3.5m-15 15c.5-3.5 2.1-5.25 3.5-5.25s3 1.75 3.5 5.25Z");
}

</style>
