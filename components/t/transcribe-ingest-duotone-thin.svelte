<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yh9u2vb-g"/><path class="pj_sixb1z"/><path class="eimg1ibhu"/><path class="cqv_tsv-n"/><path class="jldegj7_b"/><path class="cnherbc0v"/><path class="lbz2yq5no"/><path class="hcqml3bhu"/><path class="l517yxbln"/><path class="uub08b4lk"/><path class="f6k_-qbtg"/><path class="xbl1wuhge"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:transcribe-ingest-duotone-thin" {...props}></Icon>
<style>
:global(.cnherbc0v) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 17h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cqv_tsv-n) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 9h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.eimg1ibhu) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.f6k_-qbtg) {
  d: path("M16 13h3");
}

:global(.hcqml3bhu) {
  d: path("M8 6v12");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jldegj7_b) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 13h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l517yxbln) {
  d: path("M12 9v6");
}

:global(.lbz2yq5no) {
  d: path("M4 9v6");
}

:global(.pj_sixb1z) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 6v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.uub08b4lk) {
  d: path("M16 9h5");
}

:global(.xbl1wuhge) {
  d: path("M16 17h5");
}

:global(.yh9u2vb-g) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
