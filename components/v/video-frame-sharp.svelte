<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="pw7p-85ys"/><path class="mylvul_lq"/><path class="mt_lawbsd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:video-frame-sharp" {...props}></Icon>
<style>
:global(.mt_lawbsd) {
  d: path("m8.5 14.25l2.75-2.75l2 2l1.25-1.25l1.5 1.5");
}

:global(.mylvul_lq) {
  d: path("M5.75 6.75h12.5v10.5H5.75z");
}

:global(.pw7p-85ys) {
  d: path("M2.75 3.75h18.5v16.5H2.75z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
