<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="wwozeg7ww"/><path class="yih0nfb7c"/><path class="qxhe48bjs"/><path class="evq885uwk"/><path class="af7iv3n-p"/><path class="x3jkjl77t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:umbrella-open-outline-bold" {...props}></Icon>
<style>
:global(.af7iv3n-p) {
  d: path("M12 2v2.5");
}

:global(.evq885uwk) {
  d: path("m5 3 2 2");
}

:global(.qxhe48bjs) {
  d: path("M12 14v7");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wwozeg7ww) {
  d: path("M3 14a9 9 0 0 1 18 0");
}

:global(.x3jkjl77t) {
  d: path("m19 3 -2 2");
}

:global(.yih0nfb7c) {
  d: path("M3 14h18");
}

</style>
