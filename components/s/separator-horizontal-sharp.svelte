<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mj_wvt38c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:separator-horizontal-sharp" {...props}></Icon>
<style>
:global(.mj_wvt38c) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 3L19 3L19 8L5 8ZM2 12L22 12M5 16L19 16L19 21L5 21Z");
}

</style>
