<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zltmsaboc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:upload-round" {...props}></Icon>
<style>
:global(.zltmsaboc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m16 8l-4-4l-4 4m4-4v12m-8 0a4 4 0 0 0 4 4h8a4 4 0 0 0 4-4");
}

</style>
