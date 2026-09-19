<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qv3avbbbs"/><path class="by3ac43bk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-skip-next" {...props}></Icon>
<style>
:global(.by3ac43bk) {
  fill: currentColor;
  d: path("M14.5 12L6 6v12zM8 9.86L11.03 12L8 14.14zM16 6h2v12h-2z");
}

:global(.qv3avbbbs) {
  fill: currentColor;
  d: path("M8 9.86v4.28L11.03 12z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
