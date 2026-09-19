<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-id84bjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-card-membership" {...props}></Icon>
<style>
:global(.i-id84bjr) {
  fill: currentColor;
  d: path("M22 2H2v15h6v5l4-2l4 2v-5h6zm-2 13H4v-2h16zm0-5H4V4h16z");
}

</style>
