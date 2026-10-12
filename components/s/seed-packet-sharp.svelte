<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="f-k0bts7t"/><path class="yi9r3j5ah"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:seed-packet-sharp" {...props}></Icon>
<style>
:global(.f-k0bts7t) {
  d: path("M4.75 5.5L6.5 4.25L8.25 5.5L10 4.25l1.75 1.25l1.75-1.25l1.75 1.25L17 4.25l2 1.25v15.75H5v-1ZM8 17.75h8");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yi9r3j5ah) {
  d: path("M12 14.25c0-2.5-1.5-4-4-4c0 2.5 1.5 4 4 4Zm0-1.75c0-2.5 1.5-4 4-4c0 2.5-1.5 4-4 4Zm0 1.75v1.25");
}

</style>
