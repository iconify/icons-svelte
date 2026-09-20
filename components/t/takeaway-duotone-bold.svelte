<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="e8698-bge"/><path class="gd3gqxb-h"/><path class="bkfy3c96t"/><path class="hjqc4kbvp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:takeaway-duotone-bold" {...props}></Icon>
<style>
:global(.bkfy3c96t) {
  d: path("m6 11 3 -3h6l3 3");
}

:global(.e8698-bge) {
  fill: currentColor;
  d: path("M6 11v9h12v-9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.gd3gqxb-h) {
  d: path("M6 11v9h12v-9Z");
}

:global(.hjqc4kbvp) {
  d: path("M10 8a2 2 0 0 1 4 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
