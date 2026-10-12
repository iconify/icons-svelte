<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="fnudolgtt"/><path class="gz5_b-swj"/><path class="u6fu9x6fo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:selfie-stick" {...props}></Icon>
<style>
:global(.fnudolgtt) {
  width: 7px;
  height: 9.5px;
  x: 12.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

:global(.gz5_b-swj) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.25 5.75h.01");
}

:global(.u6fu9x6fo) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.25 12.25l-5 5m.53.53l-1.06-1.06q-.71-.71-1.42 0l-1.33 1.33q-.71.71 0 1.42l1.06 1.06q.71.71 1.42 0l1.33-1.33q.71-.71 0-1.42");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
