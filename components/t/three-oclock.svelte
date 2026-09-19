<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="p84kmlbje"/><circle class="rt_37l3dj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-monotone:three-oclock" {...props}></Icon>
<style>
:global(.p84kmlbje) {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m17.998 32H35.445A4 4 0 0 1 34 35.445V38h-4v-2.555A4 4 0 0 1 28.555 34h-2.553L26 30h2.555c.35-.6.845-1.096 1.445-1.445V6h4v22.555A4 4 0 0 1 35.445 30H50z");
}

:global(.rt_37l3dj) {
  cx: 32px;
  cy: 32px;
  r: 3px;
  fill: currentColor;
}

</style>
