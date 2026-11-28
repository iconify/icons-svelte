<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="eimh7ccfv"/><path clip-rule="evenodd" class="e-i_tk0nz"/><path class="wr4_szyrd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:scan-box-sharp-fill" {...props}></Icon>
<style>
:global(.e-i_tk0nz) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17 9.424V14.576L12 17L7 14.576V9.424L12 12L17 9.424Z");
  stroke: none;
}

:global(.eimh7ccfv) {
  d: path("M3 9V3H9M15 3H21V9M21 15V21H15M9 21H3V15");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.wr4_szyrd) {
  d: path("M7 9.424L12 12M12 17L17 14.576V9.424L12 7L7 9.424V14.576L12 17ZM12 12L17 9.424M12 12V17");
}

</style>
