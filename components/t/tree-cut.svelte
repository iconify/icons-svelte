<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ubtxthbxo"/><path class="r22_p6otv"/><path class="s_pznbhkp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:tree-cut" {...props}></Icon>
<style>
:global(.r22_p6otv) {
  d: path("M4.5 7.5V16c0 3.5-.5 5-2 5h19c-1.5 0-2-1.5-2-5V7.5");
}

:global(.s_pznbhkp) {
  d: path("M8 7.5a4 1.25 0 1 0 8 0a4 1.25 0 1 0-8 0ZM9 21c.5-1.5.5-3 .5-4.5M15 21c-.5-1.5-.5-3-.5-4.5");
}

:global(.ubtxthbxo) {
  d: path("M4.5 7.5a7.5 4 0 1 0 15 0a7.5 4 0 1 0-15 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
