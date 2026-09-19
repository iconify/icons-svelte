<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i1kmxjbam"/><path class="p8xec_bop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-discount" {...props}></Icon>
<style>
:global(.i1kmxjbam) {
  fill: currentColor;
  d: path("M12.79 21L3 11.21v2.83l9.79 9.79l9.04-9.04l-1.42-1.41z");
}

:global(.p8xec_bop) {
  fill: currentColor;
  d: path("m3 9.04l9.79 9.79l9.04-9.04L12.04 0H3zM7.25 3a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5");
}

</style>
