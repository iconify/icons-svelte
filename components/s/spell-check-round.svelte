<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vm-kqz9jy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:spell-check-round" {...props}></Icon>
<style>
:global(.vm-kqz9jy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 9a3 3 0 1 0 6 0a3 3 0 0 0-6 0m6-3v6m4-8v8m0-3a3 3 0 1 0 6 0a3 3 0 0 0-6 0m-1 8l3 3l6-6");
}

</style>
