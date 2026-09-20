<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="tzxtpfb7v"/><path class="yt70p9btb"/><path class="f2b86rhqr"/><path class="hpm6v1-ys"/><path class="srzgk7jml"/><path class="zohykibek"/><path class="m6nkjhiin"/><path class="jkuojibnm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:vpn-duotone-bold" {...props}></Icon>
<style>
:global(.f2b86rhqr) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 13v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hpm6v1-ys) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jkuojibnm) {
  d: path("M3 20h18");
}

:global(.m6nkjhiin) {
  d: path("M12 13v3");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.srzgk7jml) {
  d: path("M3 17a9 9 0 0 1 18 0");
}

:global(.tzxtpfb7v) {
  fill: currentColor;
  d: path("M10 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.yt70p9btb) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 17a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zohykibek) {
  d: path("M10 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
