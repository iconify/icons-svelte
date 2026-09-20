<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGEZ1BPvRc"><path class="k5-vjlrin"/><path clip-rule="evenodd" class="q5sk2r02r"/></mask></defs><circle mask="url(#SVGEZ1BPvRc)" class="bd9gczbnq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:triangle-right-circle-filled" {...props}></Icon>
<style>
:global(.bd9gczbnq) {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.k5-vjlrin) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

:global(.q5sk2r02r) {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M15.998 13L9 8.963v8.074zm2.5.866a1 1 0 0 0 0-1.732L8.5 6.365a1 1 0 0 0-1.5.866V18.77a1 1 0 0 0 1.5.866z");
}

</style>
