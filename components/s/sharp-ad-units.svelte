<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mp_rw7b0q"/><path class="h3ty8tbnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-ad-units" {...props}></Icon>
<style>
:global(.h3ty8tbnv) {
  fill: currentColor;
  d: path("M8 6h8v2H8z");
}

:global(.mp_rw7b0q) {
  fill: currentColor;
  d: path("M19 1H5v22h14zm-2 18H7V5h10z");
}

</style>
