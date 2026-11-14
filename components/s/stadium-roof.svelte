<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lpu1rmbar"/><path class="rxwbqqflb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:stadium-roof" {...props}></Icon>
<style>
:global(.lpu1rmbar) {
  d: path("M2.5 14a9.5 9 0 0 1 19 0v5h-19Zm0 0h19");
}

:global(.rxwbqqflb) {
  d: path("M12 5a4.5 9 0 0 1 4.5 9M12 5a4.5 9 0 0 0-4.5 9");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
