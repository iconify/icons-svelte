<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pyh7ymh4h"/><path class="qifilrr3z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:tag-new" {...props}></Icon>
<style>
:global(.pyh7ymh4h) {
  d: path("M2.5 5H15l6.5 7l-6.5 7H2.5ZM16 12h.01");
}

:global(.qifilrr3z) {
  d: path("M6 15.5v-7l5 7v-7");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
