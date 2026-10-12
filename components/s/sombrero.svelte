<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qlx-5obcj"/><path class="ieoqfqbzy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:sombrero" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ieoqfqbzy) {
  d: path("M2.75 12.75c1.5 2.5 3.5 4 5.75 4h7c2.25 0 4.25-1.5 5.75-4");
}

:global(.qlx-5obcj) {
  d: path("m8.5 16.75l2-9.75c.3-1.4 2.7-1.4 3 0l2 9.75ZM9.25 13h5.5");
}

</style>
