<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="risuzkbim"/><path class="sgzewgbhu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:token-unlock-schedule" {...props}></Icon>
<style>
:global(.risuzkbim) {
  d: path("M11.7 21H3.5V4.5h17v6.6M8 2.5v4m8-4v4m-12.5 3h17");
}

:global(.sgzewgbhu) {
  d: path("M14.5 17.5h7V22h-7Zm2 0v-2a2 2 0 0 1 4 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
