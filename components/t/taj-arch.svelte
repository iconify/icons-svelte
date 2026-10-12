<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fl9re4beo"/><rect class="rz1hizbkf"/><path class="sbdc7c9xu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:taj-arch" {...props}></Icon>
<style>
:global(.fl9re4beo) {
  d: path("M12 5.75c3 1.5 5 3.5 5 6c0 .9-.3 1.75-.75 2.25h-8.5C7.3 13.5 7 12.65 7 11.75c0-2.5 2-4.5 5-6m0-3v3M2.75 9.5v11.75M21.25 9.5v11.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rz1hizbkf) {
  width: 12.5px;
  height: 7.25px;
  x: 5.75px;
  y: 14px;
  rx: 1px;
}

:global(.sbdc7c9xu) {
  d: path("M10 21.25V18.5a2 2 0 0 1 4 0v2.75");
}

</style>
