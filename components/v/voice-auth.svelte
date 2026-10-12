<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ewx-x1baf"/><rect class="je-v0edny"/><path class="e6e78bc1a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:voice-auth" {...props}></Icon>
<style>
:global(.e6e78bc1a) {
  d: path("M16.25 12.25v-1.5a1.75 1.75 0 0 1 3.5 0v1.5");
}

:global(.ewx-x1baf) {
  d: path("M2.75 10v4M6 7v10M9.25 4v16M12.5 8v8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.je-v0edny) {
  width: 6.5px;
  height: 5.5px;
  x: 14.75px;
  y: 12.25px;
  rx: 1.25px;
}

</style>
