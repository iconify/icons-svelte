<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGwEhnQeKK"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="dvo306k0p"/><path class="i-yqcoe7q"/></g></mask></defs><circle mask="url(#SVGwEhnQeKK)" class="bd9gczbnq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:ticket-circle-filled" {...props}></Icon>
<style>
:global(.bd9gczbnq) {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

:global(.dvo306k0p) {
  d: path("M4 9a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v2.64c0 .47-.282.894-.716 1.075a.309.309 0 0 0 0 .57c.434.18.716.604.716 1.074V17a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2v-2.64c0-.47.282-.894.716-1.075a.309.309 0 0 0 0-.57A1.16 1.16 0 0 1 4 11.641zm16 0H6v2.161c1.208.904 1.208 2.774 0 3.678V17h14v-2.161c-1.208-.905-1.208-2.774 0-3.678z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.i-yqcoe7q) {
  d: path("M15.5 16a1 1 0 0 1 1 1v.5a1 1 0 1 1-2 0V17a1 1 0 0 1 1-1m0-8.5a1 1 0 0 1 1 1V9a1 1 0 1 1-2 0v-.5a1 1 0 0 1 1-1m0 2.75a1 1 0 0 1 1 1v.5a1 1 0 1 1-2 0v-.5a1 1 0 0 1 1-1m0 3a1 1 0 0 1 1 1v.5a1 1 0 1 1-2 0v-.5a1 1 0 0 1 1-1");
}

:global(.k5-vjlrin) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

:global(.kvn14gsjy) {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
}

</style>
