<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="x6vb0-lkk"/><path class="mgpk_ybqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noto-v1:stop-button" {...props}></Icon>
<style>
:global(.mgpk_ybqo) {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M32 32h64v64H32z");
}

:global(.x6vb0-lkk) {
  fill: none;
  d: path("M0 0h128v128H0z");
}

</style>
