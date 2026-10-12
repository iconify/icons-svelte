<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="tmtazmbsn"/><path class="yaok5yb_f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:safe-room-sharp" {...props}></Icon>
<style>
:global(.tmtazmbsn) {
  d: path("m3.92 9.31l6.91-5.62L12 2.75l1.17.94l6.91 5.62l1.17.94v11H2.75v-11z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yaok5yb_f) {
  d: path("m12 9l3.75 1.35v3c0 2.4-1.5 4.1-3.75 5.15c-2.25-1.05-3.75-2.75-3.75-5.15v-3Z");
}

</style>
