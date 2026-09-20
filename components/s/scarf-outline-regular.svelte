<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oz3eccbug"/><path class="ls_1jlbjr"/><path class="mhf9v2bnf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:scarf-outline-regular" {...props}></Icon>
<style>
:global(.ls_1jlbjr) {
  d: path("M7 8v10h4V8");
}

:global(.mhf9v2bnf) {
  d: path("M14 11v10h4V11");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oz3eccbug) {
  d: path("M7 8a5 5 0 0 1 10 0");
}

</style>
