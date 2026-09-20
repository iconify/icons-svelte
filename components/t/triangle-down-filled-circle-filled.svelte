<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGsSTXr1TV"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="v1dheebdz"/><path class="sp5_txb5b"/></g></mask></defs><circle mask="url(#SVGsSTXr1TV)" class="bd9gczbnq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:triangle-down-filled-circle-filled" {...props}></Icon>
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

:global(.kvn14gsjy) {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
}

:global(.sp5_txb5b) {
  d: path("M6.365 8.5A1 1 0 0 1 7.231 7H18.77a1 1 0 0 1 .866 1.5l-5.769 9.999a1 1 0 0 1-1.732 0zM13 13.997L15.306 10h-4.612z");
}

:global(.v1dheebdz) {
  d: path("M13.866 18.499a1 1 0 0 1-1.732 0l-5.769-10A1 1 0 0 1 7.231 7H18.77a1 1 0 0 1 .866 1.5z");
}

</style>
