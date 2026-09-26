<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cc50cvs0o"/><path class="rj4248bgl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-arrow-u-turn-left" {...props}></Icon>
<style>
:global(.cc50cvs0o) {
  d: path("M6 3H18C19.6569 3 21 4.34315 21 6V18C21 19.6569 19.6569 21 18 21H6C4.34315 21 3 19.6569 3 18V6C3 4.34315 4.34315 3 6 3Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rj4248bgl) {
  d: path("M11.8937 16.5H12.9203C14.6212 16.5 16 15.1569 16 13.5C16 11.8431 14.6212 10.5 12.9203 10.5H8.30068M10.8671 7.5L8.15034 10.1464C7.94989 10.3417 7.94989 10.6583 8.15034 10.8536L10.8671 13.5");
}

</style>
