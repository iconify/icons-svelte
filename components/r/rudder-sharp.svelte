<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="mmre-hlzn"/><path class="ye0kv3bao"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:rudder-sharp" {...props}></Icon>
<style>
:global(.mmre-hlzn) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 10V3.5m-6 0h9.5M11 10h6.5v11.25H11v-1Z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.ye0kv3bao) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.25 13h.01");
}

</style>
