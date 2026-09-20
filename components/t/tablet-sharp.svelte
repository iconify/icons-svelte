<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2y10x-if"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:tablet-sharp" {...props}></Icon>
<style>
:global(.i2y10x-if) {
  fill: currentColor;
  d: path("M2 19V5h20v14zm3.5-1h13V6h-13z");
}

</style>
