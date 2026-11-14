<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c6aefhbrw"/><path class="cmbwmdb6v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:sprint-move" {...props}></Icon>
<style>
:global(.c6aefhbrw) {
  d: path("M2.5 3.5h19v17h-19Zm9.5 0v17");
}

:global(.cmbwmdb6v) {
  d: path("M5.25 7h4v5h-4Zm9.5 2.5h4m-2-2l2 2l-2 2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
