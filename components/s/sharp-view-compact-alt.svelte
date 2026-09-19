<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f3k7jj86s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-view-compact-alt" {...props}></Icon>
<style>
:global(.f3k7jj86s) {
  fill: currentColor;
  d: path("M22 4H2v16h20zM11.5 16.5h-4v-4h4zm0-5h-4v-4h4zm5 5h-4v-4h4zm0-5h-4v-4h4z");
}

</style>
