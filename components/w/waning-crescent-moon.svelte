<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<circle class="zef_6xa6v"/><path class="aty76ab7w"/><circle class="lv9lgkpzn"/><circle class="pmf5v6-_k"/><circle class="azjjvq27p"/><circle class="d3lgltbvk"/><circle class="rxtcl02fw"/><circle class="tdtofjb8j"/><circle class="qumy_j_zf"/><circle class="zk6o_5fpx"/><circle class="qokf-1kyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:waning-crescent-moon" {...props}></Icon>
<style>
:global(.aty76ab7w) {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M36 18c0 9.941-8.059 18-18 18c-.294 0-.58-.029-.87-.043C11.239 33.393 7 26.332 7 18C7 9.669 11.239 2.607 17.13.044C17.42.03 17.706 0 18 0c9.941 0 18 8.059 18 18");
}

:global(.azjjvq27p) {
  cx: 14.5px;
  cy: 27.5px;
  r: 3.5px;
  fill: var(--svg-color--5b6876, #5b6876);
}

:global(.d3lgltbvk) {
  cx: 15px;
  cy: 6px;
  r: 2px;
  fill: var(--svg-color--5b6876, #5b6876);
}

:global(.lv9lgkpzn) {
  cx: 25.5px;
  cy: 8.5px;
  r: 3.5px;
  fill: var(--svg-color--5b6876, #5b6876);
}

:global(.pmf5v6-_k) {
  cx: 16px;
  cy: 16px;
  r: 3px;
  fill: var(--svg-color--5b6876, #5b6876);
}

:global(.qokf-1kyw) {
  cx: 26px;
  cy: 23px;
  r: 2px;
  fill: var(--svg-color--5b6876, #5b6876);
}

:global(.qumy_j_zf) {
  cx: 21px;
  cy: 31px;
  r: 1px;
  fill: var(--svg-color--5b6876, #5b6876);
}

:global(.rxtcl02fw) {
  cx: 33px;
  cy: 18px;
  r: 1px;
  fill: var(--svg-color--5b6876, #5b6876);
}

:global(.tdtofjb8j) {
  cx: 6px;
  cy: 9px;
  r: 1px;
  fill: var(--svg-color--ffcc4d, #ffcc4d);
}

:global(.zef_6xa6v) {
  cx: 18px;
  cy: 18px;
  r: 18px;
  fill: var(--svg-color--ffd983, #ffd983);
}

:global(.zk6o_5fpx) {
  cx: 4px;
  cy: 19px;
  r: 2px;
  fill: var(--svg-color--ffcc4d, #ffcc4d);
}

</style>
