<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tc7bo-bol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:toolbox-sharp" {...props}></Icon>
<style>
:global(.tc7bo-bol) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 8L19 8L22 11L22 21L2 21L2 11L5 8ZM2 14L22 14M8 11L8 17M16 11L16 17M8 8L8 3L16 3L16 8");
}

</style>
