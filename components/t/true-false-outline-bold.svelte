<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="u5rn05amy"/><path class="dt6t4bcmu"/><path class="v99mbcczu"/><path class="brz3--krt"/><path class="n8z3lbl9h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:true-false-outline-bold" {...props}></Icon>
<style>
:global(.brz3--krt) {
  d: path("m15 14 4 4");
}

:global(.dt6t4bcmu) {
  d: path("m5 8 2 2 4 -4");
}

:global(.n8z3lbl9h) {
  d: path("m19 14 -4 4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.u5rn05amy) {
  d: path("M3 4h8v8H3Z");
}

:global(.v99mbcczu) {
  d: path("M13 12h8v8h-8Z");
}

</style>
