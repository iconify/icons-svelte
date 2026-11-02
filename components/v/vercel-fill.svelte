<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hwaq4lb1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:vercel-fill" {...props}></Icon>
<style>
:global(.hwaq4lb1r) {
  fill: currentColor;
  d: path("M21.872 18.51A1 1 0 0 1 21 20H3a1 1 0 0 1-.872-1.49l9-16a1.002 1.002 0 0 1 1.744 0Z");
}

</style>
