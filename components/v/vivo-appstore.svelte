<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><rect class="p_nmiubbz"/><path class="axltk9b-m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:vivo-appstore" {...props}></Icon>
<style>
:global(.axltk9b-m) {
  d: path("M32.343 11.785a8.637 8.637 0 0 1-16.686 0m-9.85 21.852s8.218-4.807 17.182-.747c12.475 5.652 19.498-1.172 19.498-1.172");
}

:global(.p_nmiubbz) {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  rx: 5.34px;
  ry: 5.34px;
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
