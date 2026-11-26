<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ju7y0_t1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:stroke-line-join-bevel-sharp-fill" {...props}></Icon>
<style>
:global(.ju7y0_t1t) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 22L3 11L11 3L22 3M11 22L11 11L22 11");
}

</style>
