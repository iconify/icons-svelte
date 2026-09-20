<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="skpc57b1w"/><path class="eob029bnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:univlorraine" {...props}></Icon>
<style>
:global(.eob029bnf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.518 6.443l.03 22.217c-.046 7.164 6.483 14.489 18.952 12.873c-.068-2.893-.15-5.477-.184-9.202c-5.91.004-8.127-.352-8.433-4.224V6.447c-3.455-.01-6.91-.005-10.365-.005Z");
}

:global(.skpc57b1w) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.84 31.343c-4.001 2.161-7.788.674-7.974-3.435V6.248c-3.455-.01-6.91-.005-10.366-.005l.031 22.218c-.047 7.163 8.776 18.242 23.815 10.658");
}

</style>
