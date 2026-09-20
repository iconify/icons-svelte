<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="een9bablf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:title-outline" {...props}></Icon>
<style>
:global(.een9bablf) {
  fill: currentColor;
  d: path("M11.385 19V6.25H6.019V5H18v1.25h-5.365V19z");
}

</style>
