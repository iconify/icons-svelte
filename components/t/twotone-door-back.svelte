<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ej-tmznxx"/><path class="t6z7jnqnv"/><path class="w_ir-7hca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-door-back" {...props}></Icon>
<style>
:global(.ej-tmznxx) {
  fill: currentColor;
  d: path("M7 19h10V5H7zm2-8h2v2H9z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

:global(.t6z7jnqnv) {
  fill: currentColor;
  d: path("M19 19V5c0-1.1-.9-2-2-2H7c-1.1 0-2 .9-2 2v14H3v2h18v-2zm-2 0H7V5h10z");
}

:global(.w_ir-7hca) {
  fill: currentColor;
  d: path("M9 11h2v2H9z");
}

</style>
