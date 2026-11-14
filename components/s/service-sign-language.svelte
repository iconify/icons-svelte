<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yho79rl-l"/><path class="way4twfqb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:service-sign-language" {...props}></Icon>
<style>
:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.way4twfqb) {
  d: path("M14.5 8V6A1.25 1.25 0 0 1 17 6v8.5c0 4-3 6.5-6 6.5c-2.5 0-4-2-4-4");
}

:global(.yho79rl-l) {
  d: path("M7 15V8.5a1.25 1.25 0 0 1 2.5 0V13m0-5V5.5a1.25 1.25 0 0 1 2.5 0V11m0-3V4.5a1.25 1.25 0 0 1 2.5 0V11");
}

</style>
