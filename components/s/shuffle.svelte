<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d4f3eobuu"/><path class="fkykw0-ih"/><path class="tqih8-7un"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:shuffle" {...props}></Icon>
<style>
:global(.d4f3eobuu) {
  d: path("M4 7.5h2.5c4 0 7 9 11 9H20");
}

:global(.fkykw0-ih) {
  d: path("m17 13.5l3 3l-3 3m-13-3h2.5c4 0 7-9 11-9H20");
}

:global(.tqih8-7un) {
  d: path("m17 4.5l3 3l-3 3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
