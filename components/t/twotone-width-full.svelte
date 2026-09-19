<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h3cpuwblb"/><path class="gu6nyabhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-width-full" {...props}></Icon>
<style>
:global(.gu6nyabhk) {
  fill: currentColor;
  d: path("M20 4H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2M5 18H4V6h1zm12 0H7V6h10zm3 0h-1V6h1z");
}

:global(.h3cpuwblb) {
  fill: currentColor;
  d: path("M7 6h10v12H7z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
