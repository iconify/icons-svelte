<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="urcgs4lnm"/><path class="fegb59bxw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:statement-notarised" {...props}></Icon>
<style>
:global(.fegb59bxw) {
  d: path("M9 16.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm1.5 2.75l-1 2.5m4-2.5l1 2.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.urcgs4lnm) {
  d: path("M6.5 18.5h-2v-16h15v16h-2M8 6.5h8M8 10h8");
}

</style>
