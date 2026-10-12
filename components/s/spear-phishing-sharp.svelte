<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="lxqglyb3j"/><path class="umtymsyts"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:spear-phishing-sharp" {...props}></Icon>
<style>
:global(.lxqglyb3j) {
  d: path("M2.75 4.25h18.5v16H2.75z");
}

:global(.umtymsyts) {
  d: path("M2.75 5.75L12 11.5l9.25-5.75M12 11.5v3.25a2.25 2.25 0 0 1-4.5 0v-1.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
