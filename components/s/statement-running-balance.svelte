<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="aq34zxffe"/><path class="b4hu1abqx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:statement-running-balance" {...props}></Icon>
<style>
:global(.aq34zxffe) {
  d: path("M14.6 21.5H4.5v-19h15v9.4m-12-5.4H10m3 0h3.5m-9 3.5H10m3 0h3.5m-9 3.5H10m3 0h2.2m2.8 1.25V21");
}

:global(.b4hu1abqx) {
  d: path("M15.25 18.25L18 21l2.75-2.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
