<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="von0376jg"/><path fill="url(#SVGnI0HfWms)" clip-rule="evenodd" class="nq6yd2nnk"/></g><defs><linearGradient id="SVGnI0HfWms" x1="12" x2="12.024" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="wncettewz"/><stop offset=".49" class="i1z15iuqv"/><stop offset="1" class="gc2nx-bzj"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:zircuit-background" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.gc2nx-bzj) {
  stop-color: var(--svg-color--00b1c9, #00b1c9);
}

:global(.i1z15iuqv) {
  stop-color: var(--svg-color--00c537, #00c537);
}

:global(.nq6yd2nnk) {
  fill-rule: evenodd;
  d: path("M4 12a8 8 0 1 1 14.06 5.223l-6.05-6.05l-5.202 5.202l-.858.859A7.96 7.96 0 0 1 4 12m13.857 3.118l.073-.147a6.7 6.7 0 0 0 .702-2.97A6.64 6.64 0 0 0 12 5.368A6.64 6.64 0 0 0 5.37 12c0 1.034.245 2.066.708 2.985l.074.146l5.86-5.86zM12 20a7.97 7.97 0 0 0 5.214-1.932l-5.203-5.204l-5.214 5.213A7.96 7.96 0 0 0 12 20");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.von0376jg) {
  fill: var(--svg-color--092306, #092306);
  d: path("M0 0h24v24H0z");
}

:global(.wncettewz) {
  stop-color: var(--svg-color--169e00, #169e00);
}

</style>
