<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="owagcvrhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:zodiac-aquarius-fill-round" {...props}></Icon>
<style>
:global(.owagcvrhf) {
  fill: currentColor;
  d: path("m2.293 9.293l2-2a2.414 2.414 0 0 1 3.414 0l1 1a.414.414 0 0 0 .586 0l1-1a2.414 2.414 0 0 1 3.414 0l1 1a.414.414 0 0 0 .586 0l1-1a2.414 2.414 0 0 1 3.414 0l2 2a.999.999 0 1 1-1.414 1.414l-2-2a.414.414 0 0 0-.586 0l-1 1a2.414 2.414 0 0 1-3.414 0l-1-1a.414.414 0 0 0-.586 0l-1 1a2.414 2.414 0 0 1-3.414 0l-1-1a.414.414 0 0 0-.586 0l-2 2a.999.999 0 1 1-1.414-1.414m0 7l2-2a2.414 2.414 0 0 1 3.414 0l1 1a.414.414 0 0 0 .586 0l1-1a2.414 2.414 0 0 1 3.414 0l1 1a.414.414 0 0 0 .586 0l1-1a2.414 2.414 0 0 1 3.414 0l2 2a.999.999 0 1 1-1.414 1.414l-2-2a.414.414 0 0 0-.586 0l-1 1a2.414 2.414 0 0 1-3.414 0l-1-1a.414.414 0 0 0-.586 0l-1 1a2.414 2.414 0 0 1-3.414 0l-1-1a.414.414 0 0 0-.586 0l-2 2a.999.999 0 1 1-1.414-1.414");
}

</style>
