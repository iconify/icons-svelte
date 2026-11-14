<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hdc4j_jfs"/><path class="c8l3fnisj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:sky-survey" {...props}></Icon>
<style>
:global(.c8l3fnisj) {
  d: path("M7.5 5.5L8 7l1.5.5L8 8l-.5 1.5L7 8l-1.5-.5L7 7Zm9 9L17 16l1.5.5l-1.5.5l-.5 1.5L16 17l-1.5-.5L16 16Z");
}

:global(.hdc4j_jfs) {
  d: path("M3 3h18v18H3Zm9 0v18m-9-9h18");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
