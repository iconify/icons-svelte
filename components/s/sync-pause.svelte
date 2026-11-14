<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m0opjt0wt"/><path class="ejeffcbad"/><path class="bx342tcte"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:sync-pause" {...props}></Icon>
<style>
:global(.bx342tcte) {
  d: path("m9 16l3 3l-3 3m1.5-12.5v5m3-5v5");
}

:global(.ejeffcbad) {
  d: path("m15 2l-3 3l3 3m-3 11A7 7 0 0 1 7.05 7.05");
}

:global(.m0opjt0wt) {
  d: path("M12 5a7 7 0 0 1 4.95 11.95");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
