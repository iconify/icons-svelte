<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f-1-_-jfw"/><path class="oxsjddcmk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:usb-stick" {...props}></Icon>
<style>
:global(.f-1-_-jfw) {
  d: path("M8.5 2.5h7V7h-7ZM7.5 7h9v14.5h-9Zm3.25-2.25h.01m2.49 0h.01");
}

:global(.oxsjddcmk) {
  d: path("M10.5 17.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
