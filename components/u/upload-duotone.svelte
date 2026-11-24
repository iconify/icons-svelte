<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mrazc08su"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:upload-duotone" {...props}></Icon>
<style>
:global(.mrazc08su) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m16 8l-4-4l-4 4m4-4v12m-8 0v2a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2v-2");
}

</style>
