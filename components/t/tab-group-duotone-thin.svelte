<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cc-oufnuo"/><path class="iy7yjsbzg"/><path class="rsu8hn7ln"/><path class="zhdz_msdd"/><path class="lp-5xmbze"/><path class="hplfm9bcc"/><path class="ils7yp4cg"/><path class="z0j9wnbwo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tab-group-duotone-thin" {...props}></Icon>
<style>
:global(.cc-oufnuo) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 16V9l2 -2h4l2 2v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hplfm9bcc) {
  d: path("M14 16V9l2 -2h4l2 2v7");
}

:global(.ils7yp4cg) {
  d: path("M2 16h20");
}

:global(.iy7yjsbzg) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 16V9l2 -2h4l2 2v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lp-5xmbze) {
  d: path("M2 16V9l2 -2h4l2 2v7");
}

:global(.rsu8hn7ln) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 16h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z0j9wnbwo) {
  d: path("M4 19.5h16");
}

:global(.zhdz_msdd) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 19.5h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
