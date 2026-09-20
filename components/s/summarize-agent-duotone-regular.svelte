<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ckyb-n3td"/><path class="r5i32t25p"/><path class="yae9epb6o"/><path class="xwwzgkuou"/><path class="pxx-spbdi"/><path class="pi0o-3bfc"/><path class="ifhv18rgk"/><path class="t_kadbb9f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:summarize-agent-duotone-regular" {...props}></Icon>
<style>
:global(.ckyb-n3td) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7.5 8.83a3.5 3.5 0 1 1 -2.96 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ifhv18rgk) {
  d: path("M12 12h6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pi0o-3bfc) {
  d: path("M12 7h9");
}

:global(.pxx-spbdi) {
  d: path("M7.5 8.83a3.5 3.5 0 1 1 -2.96 0");
}

:global(.r5i32t25p) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 7h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t_kadbb9f) {
  d: path("M12 17h3");
}

:global(.xwwzgkuou) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 17h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yae9epb6o) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
