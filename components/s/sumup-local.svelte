<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ge2mm9vjl"/><path class="myrg0jbaq"/><circle class="cg_slhbck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:sumup-local" {...props}></Icon>
<style>
:global(.cg_slhbck) {
  cx: 32.359px;
  cy: 37.667px;
  r: 5.833px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ge2mm9vjl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.318 28.604c-5.535-5.514-5.535-14.454 0-19.968c5.535-5.515 14.51-5.515 20.046 0zm19.44 3.398c.834-4.424-.459-9.185-3.902-12.603L9.808 39.361c4.86 4.847 12.367 5.431 17.873 1.777");
}

:global(.myrg0jbaq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.116 35.181v4.972h2.486");
}

</style>
