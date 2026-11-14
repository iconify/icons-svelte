<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="twr18dlsx"/><path class="fq1iv4bjw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:window-awning" {...props}></Icon>
<style>
:global(.fq1iv4bjw) {
  d: path("m5 3l-2 9.5h18L19 3m-7 9.5v9");
}

:global(.twr18dlsx) {
  d: path("M5 3h14v18.5H5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
