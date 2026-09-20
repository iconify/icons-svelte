<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ov3s02b9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:tooltip-sharp" {...props}></Icon>
<style>
:global(.ov3s02b9d) {
  fill: currentColor;
  d: path("m12 21l-2.29-3.5H3V3h18v14.5h-6.71z");
}

</style>
