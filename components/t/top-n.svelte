<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lh4qf1bgi"/><path class="eqfs0qjqz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:top-n" {...props}></Icon>
<style>
:global(.eqfs0qjqz) {
  d: path("m11 12l1.25-1v4.5M8.5 14v7m7-4.5V21");
}

:global(.lh4qf1bgi) {
  d: path("M2.5 21v-7h6V8.5h7v8h6V21Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
