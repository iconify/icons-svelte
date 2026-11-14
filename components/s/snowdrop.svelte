<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eepjpeb_n"/><path class="yoextq5jw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:snowdrop" {...props}></Icon>
<style>
:global(.eepjpeb_n) {
  d: path("M17.5 7.5c-3 1-4 5-3 9.5l1.5-3.25l1.5 3.75l1.5-3.75L20.5 17c1-4.5 0-8.5-3-9.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yoextq5jw) {
  d: path("M8 21.5C8 10 10 4 14 4c2.5 0 3.5 1.5 3.5 3.5M8 21.5c0-3.5-2-6-4.5-7c-.5 3 1.5 6 4.5 7Z");
}

</style>
