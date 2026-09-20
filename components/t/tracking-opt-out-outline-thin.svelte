<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yix-58bnj"/><path class="moha5wbmp"/><path class="lxtc-wp5b"/><path class="s-cqkabbd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tracking-opt-out-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lxtc-wp5b) {
  d: path("m10 10 4 4");
}

:global(.moha5wbmp) {
  d: path("M22 12a12.5 12.5 0 0 1 -20 0");
}

:global(.s-cqkabbd) {
  d: path("m14 10 -4 4");
}

:global(.yix-58bnj) {
  d: path("M2 12a12.5 12.5 0 0 1 20 0");
}

</style>
