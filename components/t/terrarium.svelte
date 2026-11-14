<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="prk-hacll"/><path class="xs8da9bkf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:terrarium" {...props}></Icon>
<style>
:global(.prk-hacll) {
  d: path("M2.5 5h19v14h-19Zm0 10.5h19");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xs8da9bkf) {
  d: path("M12 15.5V11c0-2.25 1.75-3.25 4-3.25C16 10 14.25 11 12 11m0 2c-2.5 0-4-1.5-4-4c2.5 0 4 1.5 4 4");
}

</style>
