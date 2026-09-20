<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGqKfsxbfi"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="ctoep-vcv"/><path class="j1wq095vt"/></g></mask></defs><circle mask="url(#SVGqKfsxbfi)" class="bd9gczbnq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:triangle-up-filled-circle-filled" {...props}></Icon>
<style>
:global(.bd9gczbnq) {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

:global(.ctoep-vcv) {
  d: path("M12.134 7.501a1 1 0 0 1 1.732 0l5.769 10A1 1 0 0 1 18.769 19H7.23a1 1 0 0 1-.866-1.5z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.j1wq095vt) {
  d: path("M19.635 17.5a1 1 0 0 1-.866 1.5H7.23a1 1 0 0 1-.866-1.5l5.769-9.999a1 1 0 0 1 1.732 0zM13 12.003L10.694 16h4.612z");
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
