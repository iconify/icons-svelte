<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="khpwel4ry"/><path class="g7osfackl"/><path class="lsgjr5bud"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:sports-bar" {...props}></Icon>
<style>
:global(.g7osfackl) {
  d: path("M8.75 13.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

:global(.khpwel4ry) {
  d: path("M2.5 7h19v13h-19ZM12 7L8.5 3M12 7l3.5-4");
}

:global(.lsgjr5bud) {
  d: path("M9 12.25q3 2.5 6 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
