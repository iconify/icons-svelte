<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rxyd1h7sa"/><path class="j_vjjz7fj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:traffic-light-off" {...props}></Icon>
<style>
:global(.j_vjjz7fj) {
  d: path("M8 6.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM8 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm0 5.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm12.848-1a3 3 0 1 1-5.196 0m2.598-2.25v3.25");
}

:global(.rxyd1h7sa) {
  d: path("M13.8 22H5V2h9v12.1");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
