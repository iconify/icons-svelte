<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lp-5xmbze"/><path class="hplfm9bcc"/><path class="ils7yp4cg"/><path class="z0j9wnbwo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tab-group-outline-bold" {...props}></Icon>
<style>
:global(.hplfm9bcc) {
  d: path("M14 16V9l2 -2h4l2 2v7");
}

:global(.ils7yp4cg) {
  d: path("M2 16h20");
}

:global(.lp-5xmbze) {
  d: path("M2 16V9l2 -2h4l2 2v7");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.z0j9wnbwo) {
  d: path("M4 19.5h16");
}

</style>
