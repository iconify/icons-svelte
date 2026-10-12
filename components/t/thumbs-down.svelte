<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fkx1pbo5i"/><rect class="rt82_gyqh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:thumbs-down" {...props}></Icon>
<style>
:global(.fkx1pbo5i) {
  d: path("m8.25 13.75l3.5 6.5a2 2 0 0 0 3-2.2l-.9-3.55h4.65a2.25 2.25 0 0 0 2.2-2.7l-1.4-6.5a2.25 2.25 0 0 0-2.2-1.8H8.25Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rt82_gyqh) {
  width: 3px;
  height: 10.25px;
  x: 2.75px;
  y: 3.5px;
  rx: 1.25px;
}

</style>
