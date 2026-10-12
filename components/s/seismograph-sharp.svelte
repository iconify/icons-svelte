<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ytqkenlip"/><path class="dvzhdg8hu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:seismograph-sharp" {...props}></Icon>
<style>
:global(.dvzhdg8hu) {
  d: path("M2.75 12h3L8 8.5l3 7l3-7l2.25 3.5h4.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ytqkenlip) {
  d: path("M3.75 4.75h16.5v14.5H3.75z");
}

</style>
