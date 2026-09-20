<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="l8dn9jbyp"/><path class="x963bozsy"/><path class="l0nc5l-lx"/><path class="mq159kbup"/><path class="sfp0ggbri"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:stress-level-outline-bold" {...props}></Icon>
<style>
:global(.l0nc5l-lx) {
  d: path("M6 15v3");
}

:global(.l8dn9jbyp) {
  d: path("M2 15h20");
}

:global(.mq159kbup) {
  d: path("M12 15v3");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sfp0ggbri) {
  d: path("M18 15v3");
}

:global(.x963bozsy) {
  d: path("m12 8 4 4H8Z");
}

</style>
