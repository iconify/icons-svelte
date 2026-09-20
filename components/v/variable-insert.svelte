<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="judecac-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:variable-insert" {...props}></Icon>
<style>
:global(.judecac-n) {
  fill: currentColor;
  d: path("M3 17V7h18v4h-7v6zm18.6 3L18 16.425V19.5h-2V13h6.5v2h-3.1l3.6 3.6z");
}

</style>
