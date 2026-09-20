<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lqcp5xb1v"/><path class="t3vzob-fn"/><path class="md05zk1ss"/><path class="at7ws5bbl"/><path class="rm8glg-ni"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:trace-waterfall-outline-bold" {...props}></Icon>
<style>
:global(.at7ws5bbl) {
  d: path("M9.5 12h5");
}

:global(.lqcp5xb1v) {
  d: path("M4 3h16");
}

:global(.md05zk1ss) {
  d: path("M7 9h5");
}

:global(.rm8glg-ni) {
  d: path("M12 15h5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t3vzob-fn) {
  d: path("M2 12a6 6 0 0 1 6 -6h8a6 6 0 0 1 6 6 6 6 0 0 1 -6 6H8a6 6 0 0 1 -6 -6");
}

</style>
