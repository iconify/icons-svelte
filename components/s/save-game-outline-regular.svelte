<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="eq8p65fcb"/><path class="itwbxpr-a"/><path class="kct9dt-jd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:save-game-outline-regular" {...props}></Icon>
<style>
:global(.eq8p65fcb) {
  d: path("M4 4v16h16V4Z");
}

:global(.itwbxpr-a) {
  d: path("M8 4v5h8V4");
}

:global(.kct9dt-jd) {
  d: path("M8 20v-6h8v6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
