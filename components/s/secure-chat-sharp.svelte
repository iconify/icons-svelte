<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="hw-xn1khn"/><path class="e3jo1e18z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:secure-chat-sharp" {...props}></Icon>
<style>
:global(.e3jo1e18z) {
  d: path("M8.75 9.75h6.5v5h-6.5zm1.5 0V7h3.5v2.75");
}

:global(.hw-xn1khn) {
  d: path("M4.75 3.75h16.5v13.5H10l-4.5 3.5v-3.5H2.75V3.75z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
