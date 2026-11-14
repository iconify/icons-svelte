<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qarsfzbri"/><path class="qcl8h8beo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:tab-forward" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qarsfzbri) {
  d: path("M2.5 19.5h2v-13a2 2 0 0 1 2-2h11a2 2 0 0 1 2 2v13h2m-13.75-7h8.5");
}

:global(.qcl8h8beo) {
  d: path("m12.75 9l3.5 3.5l-3.5 3.5");
}

</style>
