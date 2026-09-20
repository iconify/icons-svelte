<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pxx-spbdi"/><path class="pi0o-3bfc"/><path class="ifhv18rgk"/><path class="t_kadbb9f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:summarize-agent-outline-regular" {...props}></Icon>
<style>
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

:global(.t_kadbb9f) {
  d: path("M12 17h3");
}

</style>
