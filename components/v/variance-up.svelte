<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k1e5_0bdq"/><path class="hbasqibox"/><path class="ujof44wqh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:variance-up" {...props}></Icon>
<style>
:global(.hbasqibox) {
  fill: currentColor;
  d: path("M13.5 7H19v14.5h-5.5Z");
}

:global(.k1e5_0bdq) {
  d: path("M4.5 11H10v10.5H4.5Z");
}

:global(.ujof44wqh) {
  d: path("M2.5 21.5h19M11.5 11h.75m8 0h1.25m-5.25-5.75v-3M14.5 4l1.75-1.75L18 4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
