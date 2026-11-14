<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ck38ppfsa"/><path class="jtpo8fbat"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:whisky-on-the-rocks" {...props}></Icon>
<style>
:global(.ck38ppfsa) {
  d: path("M2.5 4h19l-1.75 15q-.25 2-2.25 2h-11q-2 0-2.25-2ZM4 16.25h16");
}

:global(.jtpo8fbat) {
  d: path("m5.937 9.805l3.758-1.368l1.368 3.758l-3.758 1.368Zm7.691-3.122l3.939.695l-.695 3.939l-3.939-.695Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
