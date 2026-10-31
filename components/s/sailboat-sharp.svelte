<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qwsyhya9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:sailboat-sharp" {...props}></Icon>
<style>
:global(.qwsyhya9t) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 16L22 16L18 22L6 22ZM12 2L20 12L12 12ZM12 5L5 12L12 12M12 12L12 16");
}

</style>
