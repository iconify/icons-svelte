<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tvw8ildel"/><path class="r5ic1y8rh"/><path class="t1ic5ob8h"/><path class="oagvvr2gt"/><path class="r-klkabyr"/><path class="gvmyg7bww"/><path class="puqp14a3r"/><path class="gwbi1m5_l"/><path class="u5k3kbbab"/><path class="bie4u9bix"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:trace-request-duotone-thin" {...props}></Icon>
<style>
:global(.bie4u9bix) {
  d: path("M19 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.gvmyg7bww) {
  d: path("M2 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.gwbi1m5_l) {
  d: path("M12 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oagvvr2gt) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m6 7 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.puqp14a3r) {
  d: path("m6 7 6 6");
}

:global(.r-klkabyr) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 15h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r5ic1y8rh) {
  fill: currentColor;
  d: path("M12 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.t1ic5ob8h) {
  fill: currentColor;
  d: path("M19 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.tvw8ildel) {
  fill: currentColor;
  d: path("M2 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.u5k3kbbab) {
  d: path("M16 15h4");
}

</style>
