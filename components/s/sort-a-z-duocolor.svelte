<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="myjix-b9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:sort-a-z-duocolor" {...props}></Icon>
<style>
:global(.myjix-b9t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m4 17l3 3l3-3m-3 3V4m7 6V7a3 3 0 0 1 6 0v3m-6-2h6m-6 6h6l-6 6h6");
}

</style>
