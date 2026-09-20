<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zaau21ski"/><path class="vj8si9dha"/><path class="fa2e7y2tg"/><path class="wfg0vmbgy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:syntax-outline-thin" {...props}></Icon>
<style>
:global(.fa2e7y2tg) {
  d: path("M4 17h8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vj8si9dha) {
  d: path("m16 4 4 4 -4 4");
}

:global(.wfg0vmbgy) {
  d: path("M15 17h5");
}

:global(.zaau21ski) {
  d: path("M8 4 4 8l4 4");
}

</style>
