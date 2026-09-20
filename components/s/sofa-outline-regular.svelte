<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v6idbfb-b"/><path class="oqj-o0b2r"/><path class="owfn5sxxm"/><path class="x7yzkkbqs"/><path class="xroalcbzh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sofa-outline-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
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
