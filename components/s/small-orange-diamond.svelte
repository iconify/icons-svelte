<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="q_06f8bjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-v1:small-orange-diamond" {...props}></Icon>
<style>
:global(.q_06f8bjf) {
  fill: var(--svg-color--f6921e, #f6921e);
  d: path("M32.725 56.013L8.407 32.077l24.32-23.941l24.315 23.941z");
}

</style>
