<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-fipwsnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:type-shadow" {...props}></Icon>
<style>
:global(.c-fipwsnb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.5 20.5l.843-2.247m5.091-13.577L13.5 4.5l3.059 8.157m.702 1.873L19.5 20.5M4 19.5l6-16l6 16m-10.5-4h9");
}

</style>
