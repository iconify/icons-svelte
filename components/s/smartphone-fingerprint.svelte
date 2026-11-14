<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wb-3accoe"/><path class="igxmsl8nr"/><path class="hq3kwqb_b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:smartphone-fingerprint" {...props}></Icon>
<style>
:global(.hq3kwqb_b) {
  d: path("M10.5 10.5a1.5 1.5 0 0 1 3 0m-5 0V13m7-2.5V13M12 10.5v4");
}

:global(.igxmsl8nr) {
  d: path("M8.5 10.5a3.5 3.5 0 0 1 7 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wb-3accoe) {
  d: path("M6 2.5h12v19H6ZM10.5 18h3");
}

</style>
