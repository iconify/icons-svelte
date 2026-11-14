<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lruds70zl"/><path class="rroxk1enw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:weed-killer-warning" {...props}></Icon>
<style>
:global(.lruds70zl) {
  d: path("M12 2.5L22 21H2Z");
}

:global(.rroxk1enw) {
  d: path("M12 15c-2-1.5-2-4.5 0-7.5c2 3 2 6 0 7.5Zm0 3h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
