<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="jy2u6qbys"/><path class="smb-jnhdg"/><path class="fzqccolbq"/><path class="pz2mgtkjp"/><path class="k2-30wbbi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:soundwave-linear" {...props}></Icon>
<style>
:global(.fzqccolbq) {
  d: path("M8 7L8 17");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jy2u6qbys) {
  d: path("M12 4L12 20");
}

:global(.k2-30wbbi) {
  d: path("M4 11L4 13");
}

:global(.pz2mgtkjp) {
  d: path("M20 11L20 13");
}

:global(.smb-jnhdg) {
  d: path("M16 7L16 17");
}

</style>
