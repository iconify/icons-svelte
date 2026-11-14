<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="iee3p_blp"/><path class="p3e7cccoi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:tote-bin" {...props}></Icon>
<style>
:global(.iee3p_blp) {
  d: path("M3.5 8h17L19 20H5Zm0 0L6 5h12l2.5 3");
}

:global(.p3e7cccoi) {
  d: path("M9 11h6v2.5H9Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
