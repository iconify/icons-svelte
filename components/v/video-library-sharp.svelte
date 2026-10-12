<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="au9uyccni"/><path class="gdkel4bsw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:video-library-sharp" {...props}></Icon>
<style>
:global(.au9uyccni) {
  d: path("M2.75 7.75h15.5v13.5H2.75z");
}

:global(.gdkel4bsw) {
  d: path("M6.75 3.75h14.5v13M9.43 12.42l2.64 1.66l.68.42l-.68.42l-2.64 1.66l-.68.42v-5z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
