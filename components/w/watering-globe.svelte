<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="td7fghbsf"/><path class="z953kz5sj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:watering-globe" {...props}></Icon>
<style>
:global(.td7fghbsf) {
  d: path("M6.5 7.5a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0ZM12 13v3m-6 0h12l-1.25 5.5h-9.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z953kz5sj) {
  d: path("M12 5s-1.75 2.25-1.75 3.5a1.75 1.75 0 0 0 3.5 0C13.75 7.25 12 5 12 5Z");
}

</style>
