<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="f0nhpsynn"/><ellipse class="rarrkzbto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:user-rounded-bold-duotone" {...props}></Icon>
<style>
:global(.f0nhpsynn) {
  cx: 12px;
  cy: 6px;
  r: 4px;
  fill: currentColor;
}

:global(.rarrkzbto) {
  cx: 12px;
  cy: 17px;
  fill: currentColor;
  opacity: var(--svg-opacity--0-5, 0.5);
  rx: 7px;
  ry: 4px;
}

</style>
