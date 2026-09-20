<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rg0slsbex"/><path class="xvqqitb7t"/><path class="ftka6y45f"/><path class="s9jzbjbwv"/><path class="hf_gtezns"/><path class="sjev68umd"/><path class="oe-98mb0w"/><path class="vdq8lyksd"/><path class="vhnbtvbtn"/><path class="xyj-l9cjp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:winsorize-duotone-thin" {...props}></Icon>
<style>
:global(.ftka6y45f) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 12v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hf_gtezns) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oe-98mb0w) {
  d: path("M12 6v12");
}

:global(.rg0slsbex) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 11v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s9jzbjbwv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 8h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.sjev68umd) {
  d: path("M6 11v7");
}

:global(.vdq8lyksd) {
  d: path("M18 12v6");
}

:global(.vhnbtvbtn) {
  d: path("M3 8h18");
}

:global(.xvqqitb7t) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 6v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xyj-l9cjp) {
  d: path("M3 18h18");
}

</style>
