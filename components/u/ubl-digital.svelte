<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="eu4f51brx"/><path class="dmtbvvb8z"/><circle class="czfg_jbtf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:ubl-digital" {...props}></Icon>
<style>
:global(.czfg_jbtf) {
  cx: 40.162px;
  cy: 14.234px;
  r: 1.797px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.dmtbvvb8z) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.225 13.498c-3.355-1.121-7.29-1.767-11.498-1.767C14.451 11.731 4.5 17.224 4.5 24s9.951 12.269 22.227 12.269c6.695 0 12.698-1.634 16.773-4.218");
}

:global(.eu4f51brx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.533 18.277v11.446h5.723M13.198 18.277v7.654a3.791 3.791 0 0 0 7.583 0v-7.654M28.719 24a2.861 2.861 0 0 1 0 5.723h-4.722V18.278h4.722a2.861 2.861 0 0 1 0 5.722m0 0h-4.722");
}

</style>
