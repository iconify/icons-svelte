<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="um_bubczs"/><path class="rpr8skgtq"/><path class="ip7qw0c-r"/><path class="f0wh-k8gw"/><path class="pxx-spbdi"/><path class="pi0o-3bfc"/><path class="ifhv18rgk"/><path class="t_kadbb9f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:summarize-agent-duotone-bold" {...props}></Icon>
<style>
:global(.f0wh-k8gw) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 17h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ifhv18rgk) {
  d: path("M12 12h6");
}

:global(.ip7qw0c-r) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pi0o-3bfc) {
  d: path("M12 7h9");
}

:global(.pxx-spbdi) {
  d: path("M7.5 8.83a3.5 3.5 0 1 1 -2.96 0");
}

:global(.rpr8skgtq) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 7h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t_kadbb9f) {
  d: path("M12 17h3");
}

:global(.um_bubczs) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7.5 8.83a3.5 3.5 0 1 1 -2.96 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
