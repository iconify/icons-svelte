<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="icndgycsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-arrow-in-down-left-sharp" {...props}></Icon>
<style>
:global(.icndgycsf) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 7L3 7L3 21L17 21L17 14M21.2929 2.7071L13.1464 10.8536M22 11L13 11L13 2");
}

</style>
