<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lbz2yq5no"/><path class="hcqml3bhu"/><path class="l517yxbln"/><path class="uub08b4lk"/><path class="f6k_-qbtg"/><path class="xbl1wuhge"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:transcribe-ingest-outline-regular" {...props}></Icon>
<style>
:global(.f6k_-qbtg) {
  d: path("M16 13h3");
}

:global(.hcqml3bhu) {
  d: path("M8 6v12");
}

:global(.l517yxbln) {
  d: path("M12 9v6");
}

:global(.lbz2yq5no) {
  d: path("M4 9v6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.uub08b4lk) {
  d: path("M16 9h5");
}

:global(.xbl1wuhge) {
  d: path("M16 17h5");
}

</style>
