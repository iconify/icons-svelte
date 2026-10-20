<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c07sruk-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:train-track-sharp-two-tone" {...props}></Icon>
<style>
:global(.c07sruk-c) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.2279 2.3162L2.7721 21.6838M14.7721 2.3162L21.2279 21.6838M5 6L19 6M3 12L21 12M1 18L23 18");
}

</style>
