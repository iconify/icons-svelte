<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xq6f1f_jn"/><path class="cjh2xzbpr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:unclog-drain" {...props}></Icon>
<style>
:global(.cjh2xzbpr) {
  d: path("M6 19.5a6 2 0 1 0 12 0a6 2 0 1 0-12 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xq6f1f_jn) {
  d: path("M12 2.5v11m-6 6c0-8 12-8 12 0");
}

</style>
