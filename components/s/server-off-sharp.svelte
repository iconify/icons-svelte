<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="clb146gbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:server-off-sharp" {...props}></Icon>
<style>
:global(.clb146gbb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 10H3V3m7 1h11v6h-5m4 10H3v-6h11m-7 3h.01M2 2l20 20");
}

</style>
