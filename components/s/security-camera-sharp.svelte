<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oh7ycf8sf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:security-camera-sharp" {...props}></Icon>
<style>
:global(.oh7ycf8sf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m3.237 7.207l15.455-4.141l2.07 7.727l-15.454 4.141ZM12 13.14V17h7m0-1v5M15.605 6.999l.518 1.932");
}

</style>
