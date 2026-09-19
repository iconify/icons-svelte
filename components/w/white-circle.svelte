<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="epebgbx0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-v1:white-circle" {...props}></Icon>
<style>
:global(.epebgbx0r) {
  cx: 32px;
  cy: 32px;
  r: 31px;
  fill: var(--svg-color--d0d2d3, #d0d2d3);
}

</style>
