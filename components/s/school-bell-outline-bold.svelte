<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="g2cducv3h"/><path class="rgv-6yb3g"/><path class="hjqc4kbvp"/><path class="k-jt90-vx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:school-bell-outline-bold" {...props}></Icon>
<style>
:global(.g2cducv3h) {
  d: path("M6 17a6 6 0 0 1 12 0Z");
}

:global(.hjqc4kbvp) {
  d: path("M10 8a2 2 0 0 1 4 0");
}

:global(.k-jt90-vx) {
  d: path("M11 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.rgv-6yb3g) {
  d: path("M12 11V8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
