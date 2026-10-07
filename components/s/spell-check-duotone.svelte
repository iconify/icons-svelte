<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sqfet-bly"/><path class="s3j__thdr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:spell-check-duotone" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.s3j__thdr) {
  d: path("M16 17L18 19L22 15");
}

:global(.sqfet-bly) {
  stroke-opacity: 0.4;
  d: path("M5 9C6.6569 9 8 10.3431 8 12C8 13.6569 6.6569 15 5 15C3.3431 15 2 13.6569 2 12C2 10.3431 3.3431 9 5 9ZM8 9L8 15M12 5L12 15M12 12C12 10.3431 13.3431 9 15 9C16.6569 9 18 10.3431 18 12C18 12.3407 17.942 12.6788 17.8284 13");
}

</style>
