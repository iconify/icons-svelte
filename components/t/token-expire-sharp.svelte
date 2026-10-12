<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="owy2rxb_w"/><path class="v0xwkvbcv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:token-expire-sharp" {...props}></Icon>
<style>
:global(.owy2rxb_w) {
  d: path("M19 12a7 7 0 1 1-7-7");
}

:global(.v0xwkvbcv) {
  d: path("M12 8.5V12h3m1.42-4.42l1.06-1.06");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
