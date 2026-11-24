<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v_ptuo1cv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:university-sharp" {...props}></Icon>
<style>
:global(.v_ptuo1cv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m12 3l8 3l-8 3l-8-3zM3 21h18M20 6v3M6 12v5m4-5v5m4-5v5m4-5v5");
}

</style>
