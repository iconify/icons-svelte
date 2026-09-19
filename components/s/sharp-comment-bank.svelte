<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="io1p7oban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-comment-bank" {...props}></Icon>
<style>
:global(.io1p7oban) {
  fill: currentColor;
  d: path("M2 2v20l4-4h16V2zm17 11l-2.5-1.5L14 13V5h5z");
}

</style>
