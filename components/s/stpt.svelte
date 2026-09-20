<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nckgicb_c"/><path class="pyb-dybxv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:stpt" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.nckgicb_c) {
  fill: var(--svg-color--24aae1, #24aae1);
  d: path("M19.313 3H12l-7.312 9H12z");
}

:global(.pyb-dybxv) {
  fill: var(--svg-color--000, #000);
  d: path("M19.313 12H12l-7.312 9H12z");
}

</style>
