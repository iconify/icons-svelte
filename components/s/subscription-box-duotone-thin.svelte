<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d8r3zz4mr"/><path class="j534ltbcb"/><path class="m1mjigbsi"/><path class="d1zyr9bfc"/><path class="d1t4ffbbq"/><path class="rcpzz7b9b"/><path class="qtxvlht3c"/><path class="owoavivfm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:subscription-box-duotone-thin" {...props}></Icon>
<style>
:global(.d1t4ffbbq) {
  d: path("M8 12.5h8");
}

:global(.d1zyr9bfc) {
  d: path("M12 4v4");
}

:global(.d8r3zz4mr) {
  fill: currentColor;
  d: path("M3 6a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j534ltbcb) {
  d: path("M3 6a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.m1mjigbsi) {
  d: path("M4 8h16");
}

:global(.owoavivfm) {
  d: path("m10 15 -2 2 2 2");
}

:global(.qtxvlht3c) {
  d: path("M8 17h8");
}

:global(.rcpzz7b9b) {
  d: path("m14 10.5 2 2 -2 2");
}

</style>
