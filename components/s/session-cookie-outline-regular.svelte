<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wqh892bhx"/><path class="u84sg0ngq"/><path class="wvuc0ff5n"/><path class="y6kfzfgng"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:session-cookie-outline-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.u84sg0ngq) {
  d: path("M8 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.wqh892bhx) {
  d: path("M12 4a8 8 0 1 0 8 8 6 6 0 0 1 -8 -8");
}

:global(.wvuc0ff5n) {
  d: path("M10 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.y6kfzfgng) {
  d: path("M14 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
