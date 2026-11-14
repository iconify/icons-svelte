<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z2kv0bchq"/><path class="n5u7btygh"/><path class="khskffb4i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:route-merge" {...props}></Icon>
<style>
:global(.khskffb4i) {
  d: path("m9 18.5l3 3l3-3");
}

:global(.n5u7btygh) {
  d: path("M6 7c0 4 6 3 6 7v7m6-14c0 4-6 3-6 7");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z2kv0bchq) {
  d: path("M3.5 4.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm12 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

</style>
