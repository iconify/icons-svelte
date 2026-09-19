<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="aucn04utj"/><circle class="p89deovsh"/><circle class="iljorvysz"/><circle class="goi3u9bnw"/><circle class="ub4d63l7m"/><circle class="ge9jc-4ss"/><circle class="smfgmpbti"/><circle class="wk2b4rbah"/><circle class="t7y87xbel"/><circle class="bh08iobnd"/><circle class="w23d_qkzq"/><circle class="ssbqunfwc"/><path class="o2pzyx8rh"/><path class="k-316cb_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-deblur" {...props}></Icon>
<style>
:global(.aucn04utj) {
  cx: 6px;
  cy: 14px;
  r: 1px;
  fill: currentColor;
}

:global(.bh08iobnd) {
  cx: 10px;
  cy: 14px;
  r: 1.5px;
  fill: currentColor;
}

:global(.ge9jc-4ss) {
  cx: 3px;
  cy: 14px;
  r: 0.5px;
  fill: currentColor;
}

:global(.goi3u9bnw) {
  cx: 3px;
  cy: 10px;
  r: 0.5px;
  fill: currentColor;
}

:global(.iljorvysz) {
  cx: 6px;
  cy: 10px;
  r: 1px;
  fill: currentColor;
}

:global(.k-316cb_p) {
  fill: currentColor;
  d: path("M12 5v14c3.86 0 7-3.14 7-7s-3.14-7-7-7");
  opacity: var(--svg-opacity--0-3, 0.3);
}

:global(.o2pzyx8rh) {
  fill: currentColor;
  d: path("M12 3v2c3.86 0 7 3.14 7 7s-3.14 7-7 7v2c4.96 0 9-4.04 9-9s-4.04-9-9-9");
}

:global(.p89deovsh) {
  cx: 6px;
  cy: 18px;
  r: 1px;
  fill: currentColor;
}

:global(.smfgmpbti) {
  cx: 10px;
  cy: 21px;
  r: 0.5px;
  fill: currentColor;
}

:global(.ssbqunfwc) {
  cx: 10px;
  cy: 18px;
  r: 1px;
  fill: currentColor;
}

:global(.t7y87xbel) {
  cx: 10px;
  cy: 6px;
  r: 1px;
  fill: currentColor;
}

:global(.ub4d63l7m) {
  cx: 6px;
  cy: 6px;
  r: 1px;
  fill: currentColor;
}

:global(.w23d_qkzq) {
  cx: 10px;
  cy: 10px;
  r: 1.5px;
  fill: currentColor;
}

:global(.wk2b4rbah) {
  cx: 10px;
  cy: 3px;
  r: 0.5px;
  fill: currentColor;
}

</style>
