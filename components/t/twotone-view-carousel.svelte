<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zdbjo-bzb"/><path class="rjel2mb-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-view-carousel" {...props}></Icon>
<style>
:global(.rjel2mb-r) {
  fill: currentColor;
  d: path("M2 7h4v10H2zm5 12h10V5H7zM9 7h6v10H9zm9 0h4v10h-4z");
}

:global(.zdbjo-bzb) {
  fill: currentColor;
  d: path("M9 7h6v10H9z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
