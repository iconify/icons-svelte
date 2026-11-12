<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ub6zqacoi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-dashed-arrow-right-duotone-sharp" {...props}></Icon>
<style>
:global(.ub6zqacoi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 6V3h3m12 0h3v3m0 12v3h-3M6 21H3v-3m7-15h4m7 7v4m-7 7h-4m-7-7v-4m10 5l3-3l-3-3m3 3H8");
}

</style>
