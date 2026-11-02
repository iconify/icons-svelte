<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gg5ivhbzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:trending-down-duocolor" {...props}></Icon>
<style>
:global(.gg5ivhbzc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m3 7l5 5a1.414 1.414 0 0 0 2 0l2-2a1.414 1.414 0 0 1 2 0l7 7m-6 0h6v-6");
}

</style>
