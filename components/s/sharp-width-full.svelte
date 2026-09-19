<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gisuwpb2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-width-full" {...props}></Icon>
<style>
:global(.gisuwpb2l) {
  fill: currentColor;
  d: path("M22 4H2v16h20zM4 6h1v12H4zm16 12h-1V6h1z");
}

</style>
