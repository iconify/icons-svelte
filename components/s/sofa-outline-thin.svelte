<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v6idbfb-b"/><path class="oqj-o0b2r"/><path class="owfn5sxxm"/><path class="x7yzkkbqs"/><path class="xroalcbzh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sofa-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oqj-o0b2r) {
  d: path("M5 14h14");
}

:global(.owfn5sxxm) {
  d: path("M12 8v6");
}

:global(.v6idbfb-b) {
  d: path("M5 19V8h14v11");
}

:global(.x7yzkkbqs) {
  d: path("M2 19v-5h3");
}

:global(.xroalcbzh) {
  d: path("M22 19v-5h-3");
}

</style>
