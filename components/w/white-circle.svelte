<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="o84it3bmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:white-circle" {...props}></Icon>
<style>
:global(.o84it3bmf) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--d0d0d0, #d0d0d0);
}

</style>
