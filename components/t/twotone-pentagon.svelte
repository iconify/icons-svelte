<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vy-gjbfxv"/><path class="bah_1ol8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-pentagon" {...props}></Icon>
<style>
:global(.bah_1ol8l) {
  fill: currentColor;
  d: path("M19.63 9.78L16.56 19H7.44L4.37 9.78L12 4.44zM2 9l4 12h12l4-12l-10-7z");
}

:global(.vy-gjbfxv) {
  fill: currentColor;
  d: path("M19.63 9.78L16.56 19H7.44L4.37 9.78L12 4.44z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
