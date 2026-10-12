<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="l1sihmvho"/><path class="d6zyorbpm"/><circle class="mid5xcbxi"/><circle class="hm61d-bvp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:steam-locomotive-sharp" {...props}></Icon>
<style>
:global(.d6zyorbpm) {
  d: path("M5.25 8.25h2v2.5h-2Zm14 7l2 2.5");
}

:global(.hm61d-bvp) {
  cx: 14.75px;
  cy: 17.75px;
  r: 2.5px;
}

:global(.l1sihmvho) {
  d: path("M2.75 15.25v-10h7v4h4.75v-3.5h3v3.5h2.75v6Z");
}

:global(.mid5xcbxi) {
  cx: 6.25px;
  cy: 17.75px;
  r: 2.5px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
