<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGxsLlddvt"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="wrs0-bbex"/><path class="bkochfgwo"/></g></mask></defs><circle mask="url(#SVGxsLlddvt)" class="bd9gczbnq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:tablet-circle-filled" {...props}></Icon>
<style>
:global(.bd9gczbnq) {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

:global(.bkochfgwo) {
  d: path("M10.75 19a1 1 0 0 1 1-1h2.5a1 1 0 1 1 0 2h-2.5a1 1 0 0 1-1-1");
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

:global(.wrs0-bbex) {
  d: path("M4.5 5a2 2 0 0 1 2-2h13a2 2 0 0 1 2 2v16a2 2 0 0 1-2 2h-13a2 2 0 0 1-2-2zm15 0h-13v16h13z");
}

</style>
