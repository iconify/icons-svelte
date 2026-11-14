<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c_1jvzb2k"/><path class="g5xvcibsn"/><path class="qwk9a26js"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:turn-number-sign" {...props}></Icon>
<style>
:global(.c_1jvzb2k) {
  d: path("M5 2.5h14v12H5Zm7 12v7");
}

:global(.g5xvcibsn) {
  d: path("M9 11.5V8h5.5");
}

:global(.qwk9a26js) {
  d: path("m12.5 6l2 2l-2 2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
