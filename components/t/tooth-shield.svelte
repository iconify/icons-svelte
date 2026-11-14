<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ybk9s37ds"/><path class="qje5cd9zf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:tooth-shield" {...props}></Icon>
<style>
:global(.qje5cd9zf) {
  d: path("M12 8c-1-1-2.5-1.25-3.25-.75c-1 .75-1 2.5-.5 3.75s.5 2.5 1 4c.25 1 1 1 1.25 0l.5-2c.25-.75 1.75-.75 2 0l.5 2c.25 1 1 1 1.25 0c.5-1.5.5-2.75 1-4s.5-3-.5-3.75C14.5 6.75 13 7 12 8Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ybk9s37ds) {
  d: path("M4 3h16v8c0 5-3.5 8.5-8 10.5c-4.5-2-8-5.5-8-10.5Z");
}

</style>
