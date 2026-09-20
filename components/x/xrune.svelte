<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gg9bohboc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:xrune" {...props}></Icon>
<style>
:global(.gg9bohboc) {
  fill: var(--svg-color--28dbd1, #28dbd1);
  d: path("M7.765 13.059L15.722 3l-3.198 7.941h3.711L8.352 21l3.171-7.941z");
}

</style>
