<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lwt4ul4eh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:serverless-sharp" {...props}></Icon>
<style>
:global(.lwt4ul4eh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 3C2 8 2 16 7 21M17 3c5 5 5 13 0 18M14 6l-5 6h6l-5 6");
}

</style>
