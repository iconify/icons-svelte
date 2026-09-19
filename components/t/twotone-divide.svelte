<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bskgigbvq"/><circle class="csn7xgb_l"/><circle class="ka0uewbks"/><path class="iw7fxbbub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-divide" {...props}></Icon>
<style>
:global(.bskgigbvq) {
  fill: currentColor;
  d: path("M3 11h18v2H3z");
}

:global(.csn7xgb_l) {
  cx: 12px;
  cy: 6px;
  r: 1px;
  fill: currentColor;
  opacity: var(--svg-opacity--0-3, 0.3);
}

:global(.iw7fxbbub) {
  fill: currentColor;
  d: path("M12.003 3a3 3 0 1 1-.006 6a3 3 0 0 1 .006-6M12 5a1 1 0 1 0 0 2a1 1 0 0 0 0-2m.003 10a3 3 0 1 1-.006 6a3 3 0 0 1 .006-6M12 17a1 1 0 1 0 0 2a1 1 0 0 0 0-2");
}

:global(.ka0uewbks) {
  cx: 12px;
  cy: 18px;
  r: 1px;
  fill: currentColor;
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
