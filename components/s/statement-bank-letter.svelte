<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eoz3zibrm"/><path class="ko09bfw5e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:statement-bank-letter" {...props}></Icon>
<style>
:global(.eoz3zibrm) {
  d: path("M4.5 2.5h15v19h-15Z");
}

:global(.ko09bfw5e) {
  d: path("m7.5 9.25l4.5-3.5l4.5 3.5ZM8 12.5h8m-8 3h8m-8 3h4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
