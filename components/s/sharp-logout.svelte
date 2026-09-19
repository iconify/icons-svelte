<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-r383bvg"/><path class="cooa6dyoq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-logout" {...props}></Icon>
<style>
:global(.cooa6dyoq) {
  fill: currentColor;
  d: path("m21 12l-4-4v3H9v2h8v3z");
}

:global(.f-r383bvg) {
  fill: currentColor;
  d: path("M5 5h7V3H3v18h9v-2H5z");
}

</style>
