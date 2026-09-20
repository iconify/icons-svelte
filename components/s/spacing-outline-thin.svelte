<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r3faxubne"/><path class="ws1d0fbts"/><path class="uxyzhxvwz"/><path class="ajea6vpsn"/><path class="tuynf1bdi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:spacing-outline-thin" {...props}></Icon>
<style>
:global(.ajea6vpsn) {
  d: path("m9 10 -2 2 2 2");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.tuynf1bdi) {
  d: path("m15 10 2 2 -2 2");
}

:global(.uxyzhxvwz) {
  d: path("M7 12h10");
}

:global(.ws1d0fbts) {
  d: path("M20 4v16");
}

</style>
