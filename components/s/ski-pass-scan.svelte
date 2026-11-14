<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x0heopz6i"/><path class="b09cfq0hi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ski-pass-scan" {...props}></Icon>
<style>
:global(.b09cfq0hi) {
  d: path("M8 6.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM6.5 15.5l3-4l3 4m5.5.5a3.25 3.25 0 0 1 0 4m2.25-5.75a6 6 0 0 1 0 7.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x0heopz6i) {
  d: path("M14.9 19.5H3.5v-17h12v11.9m0 2.9v1.4");
}

</style>
