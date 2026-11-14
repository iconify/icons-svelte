<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vra0bdniw"/><path class="my609aclq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:tooth-numbered" {...props}></Icon>
<style>
:global(.my609aclq) {
  d: path("M13.523 13.909L14 12c.25-1.5 1.25-2.5 1.25-4s-.5-2.5-1.75-2.5c-1 0-1.5.5-2.5.5s-1.5-.5-2.5-.5c-1.25 0-1.75 1-1.75 2.5s1 2.5 1.25 4l.5 2c.25.75 1 .75 1.25 0l.5-2c.25-.5 1.25-.5 1.5 0l.5 2c.1.301.282.482.479.541M17 15.5V22m3-6.5V22m-4.5-5.25H22m-6.5 3H22");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vra0bdniw) {
  d: path("M12.7 21.5H2.5v-19h19v10.2");
}

</style>
