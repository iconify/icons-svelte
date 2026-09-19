<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="nd4ph-hjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:white-medium-small-square" {...props}></Icon>
<style>
:global(.nd4ph-hjk) {
  fill: var(--svg-color--d0d0d0, #d0d0d0);
  d: path("M12 12h40v40H12z");
}

</style>
