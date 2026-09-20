<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xijx_-bbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:straight-outline-sharp" {...props}></Icon>
<style>
:global(.xijx_-bbu) {
  fill: currentColor;
  d: path("M11.5 20V5.883L9.38 7.996l-.688-.688L12 4l3.308 3.308l-.689.688L12.5 5.883V20z");
}

</style>
