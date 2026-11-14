<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f4dfu6tfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:thermometer" {...props}></Icon>
<style>
:global(.f4dfu6tfv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 14V5.5a2 2 0 0 1 4 0V14a4 4 0 1 1-4 0Zm7-7.5h2m-2 3h2m-2 3h2");
}

</style>
