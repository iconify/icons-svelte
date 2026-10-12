<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="zpotb2bui"/><path class="zun_w-eha"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:u-turn-sharp" {...props}></Icon>
<style>
:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zpotb2bui) {
  d: path("M5.5 3.75v11a4.75 4.75 0 0 0 9.5 0V4.25");
}

:global(.zun_w-eha) {
  d: path("M11.5 7.5L15 4l3.5 3.5");
}

</style>
