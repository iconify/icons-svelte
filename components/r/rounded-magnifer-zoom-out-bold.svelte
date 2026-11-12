<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGzADSHeme"><g class="ft5dv1b6b"><path class="w9c06acrm"/><path clip-rule="evenodd" class="kqrobaccw"/><path clip-rule="evenodd" class="nkv2sfb4k"/></g></mask></defs><path mask="url(#SVGzADSHeme)" class="w49j0rbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rounded-magnifer-zoom-out-bold" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.kqrobaccw) {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M8.024 11.157c0-.4.324-.723.723-.723h4.82a.723.723 0 0 1 0 1.446h-4.82a.723.723 0 0 1-.723-.723");
}

:global(.nkv2sfb4k) {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M18.838 18.838a.723.723 0 0 1 1.023 0l1.927 1.928a.723.723 0 0 1-1.022 1.022l-1.928-1.927a.723.723 0 0 1 0-1.023");
}

:global(.w49j0rbvv) {
  fill: currentColor;
  d: path("M0 0h24v24H0z");
}

:global(.w9c06acrm) {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.313 11.157a9.157 9.157 0 1 1-18.313 0a9.157 9.157 0 0 1 18.313 0");
}

</style>
