<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ez4kybz4i"/><path class="l-vg4sbvj"/><path class="f48e5dbbd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:variable" {...props}></Icon>
<style>
:global(.ez4kybz4i) {
  d: path("M9 6h12.5v12H9Zm-6.5 6H9");
}

:global(.f48e5dbbd) {
  d: path("M12.5 15c2 0 3-6 5-6");
}

:global(.l-vg4sbvj) {
  d: path("m6 9l3 3l-3 3m6.5-6c2 0 3 6 5 6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
