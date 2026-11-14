<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e55u7qbis"/><path class="qxqw3_bzs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:wheelchair-boarding" {...props}></Icon>
<style>
:global(.e55u7qbis) {
  d: path("M9 3.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM10.5 8v4H16l1.75 3.5");
}

:global(.qxqw3_bzs) {
  d: path("M11.75 9.103a4.5 4.5 0 1 1-6.147 6.147M2.5 22l19-3.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
