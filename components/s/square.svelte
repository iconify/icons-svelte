<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p2w5yo1lz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:square" {...props}></Icon>
<style>
:global(.p2w5yo1lz) {
  fill: currentColor;
  d: path("M3 21V3h18v18z");
}

</style>
