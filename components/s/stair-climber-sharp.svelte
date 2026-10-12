<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ep2k6ixep"/><circle class="n-vrqob0o"/><path class="hvwhfobtw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:stair-climber-sharp" {...props}></Icon>
<style>
:global(.ep2k6ixep) {
  d: path("M2.75 21.25H7v-3.5h4.75v-3.5h4.75v-3.5h4.75");
}

:global(.hvwhfobtw) {
  d: path("m9 7.25l1.25 3.25m0 0l-.75 7.25m.75-7.25l3.5 1l-.25 2.75m-4-5.75l3 1L14 7.75");
}

:global(.n-vrqob0o) {
  cx: 8.75px;
  cy: 4.5px;
  r: 1.75px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
