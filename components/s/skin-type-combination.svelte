<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zdgu3ybil"/><path class="v5yjpiyql"/><path class="ue4xr0uex"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:skin-type-combination" {...props}></Icon>
<style>
:global(.ue4xr0uex) {
  d: path("M7.5 11.5h.01m8.99 0h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v5yjpiyql) {
  fill: currentColor;
  d: path("M9.5 6.5h5a1.5 1.5 0 0 1 0 3h-1v5a1.5 1.5 0 0 1-3 0v-5h-1a1.5 1.5 0 0 1 0-3Z");
}

:global(.zdgu3ybil) {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0Z");
}

</style>
