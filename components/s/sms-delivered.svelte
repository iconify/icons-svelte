<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bb06kc7-w"/><path class="it2xttbfu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:sms-delivered" {...props}></Icon>
<style>
:global(.bb06kc7-w) {
  d: path("M6 16.25A8.5 7.5 0 1 1 9 18l-5.5 2Z");
}

:global(.it2xttbfu) {
  d: path("m8 11l3 3l5-5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
