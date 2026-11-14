<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fdinxmeob"/><path class="e48qm2udo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:spring-scale-hook" {...props}></Icon>
<style>
:global(.e48qm2udo) {
  d: path("M12 5.75v1.5l4 1.5l-8 2.5l8 2.5l-4 1.5v3.25a2.25 2.25 0 0 1-4.5 0v-1");
}

:global(.fdinxmeob) {
  d: path("M10.25 4a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
