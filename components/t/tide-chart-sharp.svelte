<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ixfmy2crh"/><path class="f31x8nbqh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:tide-chart-sharp" {...props}></Icon>
<style>
:global(.f31x8nbqh) {
  d: path("M5.5 15.25c.8-2.75 2.45-2.75 3.25 0s2.45 2.75 3.25 0s2.45-2.75 3.25 0s2.45 2.75 3.25 0m-4.75-4.75V6.75m-1.5 1.5l1.5-1.5l1.5 1.5m2-1.5v3.75M15.75 9l1.5 1.5l1.5-1.5");
}

:global(.ixfmy2crh) {
  d: path("M2.75 4h18.5v16H2.75z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
