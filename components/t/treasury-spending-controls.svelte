<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zbrsesfxm"/><path class="qal8x1xfb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:treasury-spending-controls" {...props}></Icon>
<style>
:global(.qal8x1xfb) {
  d: path("M15.75 16a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm2 4a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zbrsesfxm) {
  d: path("M12.2 19H2.5V5h19v8.2m-19-3.7h19M15 16h6m-6 4h6");
}

</style>
