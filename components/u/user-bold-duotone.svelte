<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="f0nhpsynn"/><path class="bxpukbbcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:user-bold-duotone" {...props}></Icon>
<style>
:global(.bxpukbbcg) {
  fill: currentColor;
  d: path("M20 17.5C20 19.9853 20 22 12 22C4 22 4 19.9853 4 17.5C4 15.0147 7.58172 13 12 13C16.4183 13 20 15.0147 20 17.5Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.f0nhpsynn) {
  cx: 12px;
  cy: 6px;
  r: 4px;
  fill: currentColor;
}

</style>
